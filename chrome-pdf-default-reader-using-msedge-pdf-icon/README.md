# Setting a PDF icon when Chrome Browser is the default for PDF file type on Windows 11
On Windows 11 for when you make your Chrome Browser the default app for opening PDF files, which initially causes all your PDF files to show with using the Chrome Browser icon in File Explorer.

This registry key file uses the natively embedded PDF icon in the Microsoft Edge browser `msedge.exe` file, as Chrome Browser exe file doesn't appear to have one (yet?). This also assumes that you have Microsoft Edge installed also.

Of course you choice of icon file youis governed by the file path on [this line in the registry file.](HKCR-HKLM-for-ChromePDF.reg#L17)

In this example the icon number 13 from the `msedge.exe` file is being used.
