# Alliance VE Norm Rules
The main folder of this repository contains the code for each Primo VE Local Display Field in development by the NRSG.  It also contains any out-of-the-box (OTB) display fields that are being edited by the NRSG.

# Optional Code
The Optional Code directory contains code snippets that can be added to any display field rule in VE (OTB or Local Display fields) to customize what data displays in that field.  For example, one snippet shows how to include data from fields that contain $5 (denotes that the field data is specific to a specific institution).

# Naming conventions for files in repository:

• Ex Libris rules are prefixed with "OTB_".

• Rule "section" (Display, Search, Facet) is given.

• Pre-indexed fields have the field name shown.

• Local fields have their number shown (e.g., lf01, lf53, lf100) and a label showing the purpose of the field (e.g., DOI, reproduction note, etc.).

Examples include:

	Pre-indexed field, Ex Libris rule: OTB_Display_AddedTitles.txt

	Pre-indexed field, NRSG rule: Display_AddedTitles.txt

	Local field: NRSG rule: Display_lf01_DOI.txt
