# OCR
multi script OCR using Google OCR API
Download it to any linux box box and do the following steps.
Setup JDK 1.8 on your machine. Follow instructions as in here - https://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html
Cop the attached credentials file into a folder called ".oauth-credentials" under the home folder of the user.
Extract the zip file to a folder
Start a terminal window at the folder where you unzipped the ocr tool.  
From there execute the following command.
./ocr src=<full path to the folder where you have placed all the pdf files to be ocr'd. 
The result of the ocr will be found under the folder where you have placed the pdf files under separate folder for each pdf file.
