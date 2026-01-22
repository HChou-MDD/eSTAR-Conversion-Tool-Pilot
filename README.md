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
  	  The latest release of the tool can be found in "Release" section in the right side panel.
  	
3.	Select Files:
   
     PDF File: A file dialog will appear prompting you to select a PDF file.
  	
4.	Extraction and Folder Creation:
   
     The tool will extract the embedded files from the PDF and organize them based in the XML file.
     Files will be placed into specific folders based on the chapter name mappings provided in the code.
  	
5.	Exported Files Location:
   
     The extracted files will be placed in a folder located at the same folder location of the conversion tool in Exported Files by default.
     After processing, the tool will zip the exported files into a .zip archive, stored in the same folder location of the conversion tool as eSTAR ToC Submission.zip.
  	
6.	Complete the Process:
   
     Once the extraction is complete, you will receive a message box notification showing the location of the exported zip file.
     The original extracted files folder will be removed after the zip file is created.

## Troubleshooting:
1.	Windows Security warning: "Windows protected your PC"
   
     Right click on eSTAR_ConversionTool.exe. Select "Properties", "General" tab will show. Check "Unblock" in Attributes.

2. Nothing is showing after double clicking conversion tool, or only a empty window showing.

    The currernt pilot verison conversion tool is known to have a longer response time. We kindly ask for your patience for a minute or two waiting for the File selection dialog to popup. If not, please try to close and open conevrsion tool again.     

3.	Error: "File is open. Please close the document to continue."
   
     This message appears if the selected PDF file is open. Please close the file and run the tool again.
  	



