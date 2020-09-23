<div align="center">

## Control Panel


</div>

### Description

All of control panel settings commands.

1. "rundll32.exe shell32.dll, Control_RunDLL intl.cpl,,0" makes page 0 of reginal and language settings (control panel) open.

2. "rundll32.exe shell32.dll, Control_RunDLL main.cpl,,0" makes page 0 of mouse settings (control panel) open.

3. "rundll32.exe shell32.dll, Control_RunDLL sysdm.cpl,,0" makes page 0 of system settings (control panel) open.

4. "rundll32.exe shell32.dll, Control_RunDLL nusrmgr.cpl,,0" makes page 0 of user (control panel) open.

5. "rundll32.exe shell32.dll, Control_RunDLL mmsys.cpl,,0" makes page 0 of sound settings (control panel) open.

6. "rundll32.exe shell32.dll, Control_RunDLL firewall.cpl,,0" makes page 0 of firewall settings (control panel) open.

7. "rundll32.exe shell32.dll, Control_RunDLL desk.cpl,,0" makes page 0 of display settings (control panel) open.

8. "rundll32.exe shell32.dll, Control_RunDLL timedate.cpl,,0" makes page 0 of time/date settings (control panel) open.

9. "rundll32.exe shell32.dll, Control_RunDLL hdwwiz.cpl,,0" makes page 0 of hardware (control panel) open.

10. "rundll32.exe shell32.dll, Control_RunDLL inetcpl.cpl,,0" makes page 0 of internet options (control panel) open.

11. "rundll32.exe shell32.dll, Control_RunDLL joy.cpl,,0" makes page 0 of joypad settings (control panel) open.

12. "rundll32.exe shell32.dll, Control_RunDLL powercfg.cpl,,0" makes page 0 of power settings (control panel) open.

13. "rundll32.exe shell32.dll, Control_RunDLL telephon.cpl,,0" makes page 0 of telephone and modem settings (control panel) open.

14. "rundll32.exe shell32.dll, Control_RunDLL netsetup.cpl,,0" makes page 0 of wireless network settings (control panel) open.

15. "rundll32.exe shell32.dll, Control_RunDLL wscui.cpl,,0" makes page 0 of windows security (control panel) open.

By changing the ",,0" to ",,1" and ... you can see the other pages.

Do it by SHELL command.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[iLDEREMi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ilderemi.md)
**Level**          |Advanced
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-system-services__1-35.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ilderemi-control-panel__1-66815/archive/master.zip)





### Source Code

```
Shell "rundll32.exe shell32.dll, Control_RunDLL intl.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL main.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL sysdm.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL nusrmgr.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL mmsys.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL firewall.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL desk.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL timedate.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL hdwwiz.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL inetcpl.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL joy.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL powercfg.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL telephon.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL netsetup.cpl,,0"
Shell "rundll32.exe shell32.dll, Control_RunDLL wscui.cpl,,0"
```

