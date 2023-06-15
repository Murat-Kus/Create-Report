# Create-Report
Explanation of the COBOL program

TL;DR :

The COBOL program reads a file of stock items and writes a report of the items to another file. The report includes the item code, name, and price.

Explanation :

The COBOL program reads a file of stock items and writes a report of the items to another file. The report includes the item code, name, and price.

The program uses two file descriptors, ITEM-REPORT and ITEM-FILE, to read and write files. It also defines several data structures, including PAGE-HEADING, PAGE-FOOTING, HEADS, ITEM-DETAIL-LINE, and REPORT-FOOTING, to format the report.

The PROCEDURE DIVISION section of the program contains several paragraphs that perform different tasks. The OPEN paragraph opens the input and output files. The PRINT-PAGE-HEADING paragraph writes the page heading to the report. The PRINT-REPORT-BODY paragraph reads each record from the input file, formats it, and writes it to the output file. The CLOSE paragraph closes the input and output files.
