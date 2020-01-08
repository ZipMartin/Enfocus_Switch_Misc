# Enfocus_Switch_Misc
Various mini solutions for Enfocus Switch Scripting

BusCardGrouper
Scenario: 
Business cards getting imposed 24-up need to get grouped in 24, 12, 8, 6, 4, 3, 2 or 1 to neatly work out on the sheet. This script takes in a folder of one-up PDF files. (Non .pdf files in the folder are ignored) It breaks the files into folders with quantities listed above for more efficient placement on a 24-up imposition. When there are more than 48 files, for instance, it creates separate folders; each with 24 files.
Example:
37 PDF files in a folder is received. The script creates the following folders: 1 with 24 files, 1 with 12 files and 1 with 1 file.
59 PDF files in a folder is received. The results are: 2 with 24 files each, 1 with 8 files and 1 with 3 files.
