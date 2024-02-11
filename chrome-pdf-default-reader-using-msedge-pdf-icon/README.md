# Setting a PDF icon when Chrome Browser is the default for PDF file type on Windows 11
Created to address on Windows 11 when you make your Chrome Browser the default app for opening PDF files, only to find that all your PDF files showing up as having the Chrome Browser icon in File Explorer.

This registry key file uses the PDF icon that is natively embedded in the msedge.exe file from the Microsoft Edge browser as Chrome doesn't appear to have one (yet?), assuming that you also have Microsoft Edge installed on your system.

Of course you can change which file to refer to has the icon file you wish to use simply by amending the file path accordingly on [this line of the registry file](HKCR-HKLM-for-ChromePDF.reg#L16)

In this example I use the icon at index 13 within the msedge.exe file at the path shown.
