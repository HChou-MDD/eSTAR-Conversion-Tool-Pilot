# eSTAR File Conversion Tool

## Overview
Python Conversion Tool is a file conversion tool that allows users to extract and organize embedded files from PDF. It processes the attached files in the Health Canada (HC) eSTAR PDF, organizes them based on predefined chapter names, and extracts the attachments into International Medical Device Regulators Forum (IMDRF) Table of Content (ToC) structured folders.

## Features:

•	Extracts embedded attachment files from a given PDF.
•	Organizes extracted files into subfolders based on predefined chapter data.
•	Uses predefined chapter mappings for structured folder naming.
•	Compresses extracted files into a zip archive after processing.
•	Copy orignal completed HC eSTAR PDF into output ToC zipped folders with removal of attachments to met HC submission requirments.


## How to Use:
1.	Launch the Tool:
     Run the Python app eSTAR_ConversionTool.exe to start the tool.
  	
2.	Select Files:
     PDF File: A file dialog will appear prompting you to select a PDF file.
  	
3.	Extraction and Folder Creation:
     The tool will extract the embedded files from the PDF and organize them based in the XML file.
     Files will be placed into specific folders based on the chapter name mappings provided in the code.
  	
4.	Exported Files Location:
     The extracted files will be placed in a folder located at the same folder location of the conversion tool in Exported Files by default.
     After processing, the tool will zip the exported files into a .zip archive, stored in the same folder location of the conversion tool as Extracted_Files.zip.
  	
5.	Complete the Process:
     Once the extraction is complete, you will receive a message box notification showing the location of the exported zip file.
     The original extracted files folder will be removed after the zip file is created.

## Troubleshooting:
1.	Windows Security warning: "Windows protected your PC"
     i.   Right click on eSTAR_ConversionTool.exe
  	ii.  Select "Properties", "General" tab will show
  	iii. Check "Unblock" in Attributes.
   
3.	Error: "File is open. Please close the document to continue."
     This message appears if the selected PDF file is open. Please close the file and run the tool again.
  	



