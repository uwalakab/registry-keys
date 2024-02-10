# Setting a PDF icon when Chrome Browser is the default for PDF file type on Windows 11
This was created to help address when you make your Chrome Browser on Windows 11 the default app for opening PDF files, only to find that all your PDF files showing up as having the Chrome Browser icon.

This registry key hack uses the PDF icon that is natively embedded in the msedge.exe file, assuming that also have Microsoft Edge installed on your system.

Of course you can change which file has the icon file you wish to use my amending the file path accordingly on [this line of the registry file](chrome-pdf-default-reader-using-msedge-pdf-icon/HKCR-HKLM-for-ChromePDF.reg#L16)

In this example I use the icon at index 13 within the msedge.exe file at the given path.
