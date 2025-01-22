# Windows Screen Lock Registry hacks
Below eample - The screen goes in Standby mode 10 seconds after locking the Windows console.

```
powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 10
powercfg.exe /setdcvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 10
powercfg.exe /setactive SCHEME_CURRENT
```
## Reference links
Windows lock screen power save - BEST ONE use powercfg.exe command like in the example above<br>
https://docs.microsoft.com/en-us/troubleshoot/windows-client/shell-experience/monitor-powers-off-when-pc-locked

When IDLE<br>
https://www.windows11forums.com/articles/lock-windows-11-computer-after-inactivity.11/

Screen Lock<br>
https://www.elevenforum.com/t/enable-or-disable-require-sign-in-on-wakeup-in-windows-11.864/
