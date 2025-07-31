# Setting a PDF icon when Chrome Browser is the default for PDF file type on Windows 11
On Windows 11 when you make your Chrome Browser the default app for opening PDF files, it initially causes all your PDF files to show the Chrome Browser icon in File Explorer.

The registry key file in this repository assumes you have the Edge browser installed and uses the natively embedded PDF icon from the Microsoft Edge browser `msedge.exe` file. The Chrome Browser `chrome.exe` file doesn't appear to have an embedded PDF icon (yet?).

Of course your choice of icon file is governed by the file path on [this line in the registry file.](HKCR-HKLM-for-ChromePDF.reg#L17)

In this example, the icon number 13 embedded in the `msedge.exe` file is being used.<br>
Feedback has been sent to Google to see if they could add their own PDF icon to the `chrome.exe` file, which would be a "nice to have".

_(NOTE: The icon index changed from 13 to 11 in the msedge.exe file. Registry key has been updated to reflect this)_

There is also a PowerShell script which does this and the icon refresh [at this link here.](https://github.com/uwalakab/PowerShell-Scripts/tree/main/Set-PDF-Icon-for-Chrome)
