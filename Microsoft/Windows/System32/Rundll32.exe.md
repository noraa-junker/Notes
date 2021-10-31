# Rundll32.exe

```
Rundll32.exe file
```

This file launches an 32-Bit DLL file.

## Arguments
### `file`
The dll file.

## Examples

<table class="cms_table_grid" width="100%"><tbody><tr valign="top" class="cms_table_grid_tr" style="background-color: #CCCCCC"><td class="cms_table_grid_td"><font size="5"><b>Function</b></font></td>
<td class="cms_table_grid_td"><font size="5"><b>Rundll32 command</b></font></td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">About Windows</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,ShellAbout</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Add Network Location Wizard</td>
<td class="cms_table_grid_td">Rundll32 %SystemRoot%\system32\shwebsvc.dll,AddNetPlaceRunDll</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Add Printer Wizard</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL AddPrinter</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Add Standard TCP/IP Printer Port Wizard</td>
<td class="cms_table_grid_td">Rundll32.exe tcpmonui.dll,LocalAddPortUI</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Control Panel</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Date and Time</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL timedate.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Date and Time - Additional Clocks tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Desktop Icon Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Device Installation Settings</td>
<td class="cms_table_grid_td">Rundll32.exe %SystemRoot%\System32\newdev.dll,DeviceInternetSettingUi</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Device Manager</td>
<td class="cms_table_grid_td">Rundll32.exe devmgr.dll DeviceManager_Execute</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Display Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL desk.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Ease of Access Center</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL access.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Environment Variables</td>
<td class="cms_table_grid_td">Rundll32.exe sysdm.cpl,EditEnvironmentVariables</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">File Explorer Options - General tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Options_RunDLL 0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">File Explorer Options - Search tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Options_RunDLL 2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">File Explorer Options - View tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Options_RunDLL 7</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Fonts folder</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL FontsFolder</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Forgotten Password Wizard</td>
<td class="cms_table_grid_td">Rundll32.exe keymgr.dll,PRShowSaveWizardExW</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Game Controllers</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL joy.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Hibernate or Sleep</td>
<td class="cms_table_grid_td">Rundll32.exe powrprof.dll,SetSuspendState</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Indexing Options</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL <font color="#101010"><span style="font-family: &amp;amp">srchadmin.dll</span></font></td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Infared</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL irprops.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete all browsing history</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 255</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete all browsing history and add-ons history</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 4351</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete cookies and website data</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete download history</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 16384</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete form data</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 16</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete history</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete passwords</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 32</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - delete temporary Internet files and website files</td>
<td class="cms_table_grid_td">Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 8</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Explorer - Organize Favorites</td>
<td class="cms_table_grid_td">Rundll32.exe shdocvw.dll,DoOrganizeFavDlg</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - General tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Security tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Privacy tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Content tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Connections tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,4</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Programs tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,5</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Internet Properties - Advanced tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,6</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Keyboard Properties</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.<font color="#000000">cpl</font><font color="#000000"> @1</font></td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Lock PC</td>
<td class="cms_table_grid_td">Rundll32.exe user32.dll,LockWorkStation</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Map Network Drive wizard</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL Connect</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Button swap left and right button function</td>
<td class="cms_table_grid_td">Rundll32.exe user32.dll,SwapMouseButton</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Properties - Buttons tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Properties - Pointers tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Properties - Pointer Options tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Properties - Wheel tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.cpl,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Mouse Properties - Hardware tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL main.cpl,,4</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Network Connections</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL ncpa.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">ODBC Data Source Administrator</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL odbccp32.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Offline Files (General tab)</td>
<td class="cms_table_grid_td">Rundll32.exe Shell32.dll,Control_RunDLL cscui.dll,,0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Offline Files (Disk Usage tab)</td>
<td class="cms_table_grid_td">Rundll32.exe Shell32.dll,Control_RunDLL cscui.dll,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Offline Files (Encryption tab)</td>
<td class="cms_table_grid_td">Rundll32.exe Shell32.dll,Control_RunDLL cscui.dll,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Offline Files (Network tab)</td>
<td class="cms_table_grid_td">Rundll32.exe Shell32.dll,Control_RunDLL cscui.dll,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Pen and Touch</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL tabletpc.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Personalization - Background Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Power Options</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL powercfg.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Printer User Interface</td>
<td class="cms_table_grid_td">Rundll32.exe Printui.dll,PrintUIEntry /?</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Printers folder</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL PrintersFolder</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Process idle tasks</td>
<td class="cms_table_grid_td">Rundll32.exe advapi32.dll,ProcessIdleTasks</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Programs and Features</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Region - Formats tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Intl.cpl,,0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Region - Location tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Intl.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Region - Administrative tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Intl.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Safely Remove Hardware</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL HotPlug.dll</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Screen Saver Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Security and Maintenance</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL wscui.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Set Program Access and Computer Defaults</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Set Up a Network wizard</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL NetSetup.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Sleep or Hibernate</td>
<td class="cms_table_grid_td">Rundll32.exe powrprof.dll,SetSuspendState</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Sound - Playback tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Mmsys.cpl,,0</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Sound - Recording tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Mmsys.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Sound - Sounds tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Mmsys.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Sound - Communications tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Mmsys.cpl,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Speech Properties - Text to Speech tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL %SystemRoot%\System32\Speech\SpeechUX\sapi.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Start Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Options_RunDLL 3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Stored User Names and Passwords</td>
<td class="cms_table_grid_td">Rundll32.exe keymgr.dll,KRShowKeyMgr</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">System Properties - Computer Name tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Sysdm.cpl,,1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">System Properties - Hardware tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Sysdm.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">System Properties - Advanced tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Sysdm.cpl,,3</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">System Properties - System Protection tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Sysdm.cpl,,4</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">System Properties - Remote tab</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL Sysdm.cpl,,5</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Taskbar Settings</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Options_RunDLL 1</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Text Services and Input Languages</td>
<td class="cms_table_grid_td">Rundll32.exe Shell32.dll,Control_RunDLL input.dll,,{C07337D3-DB2C-4D0B-9A93-B722A6C106E2}</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">User Accounts</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL nusrmgr.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Windows Features</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,2</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Windows Firewall</td>
<td class="cms_table_grid_td">Rundll32.exe shell32.dll,Control_RunDLL firewall.cpl</td>
</tr>
<tr valign="top" class="cms_table_grid_tr"><td class="cms_table_grid_td">Windows To Go Startup Options</td>
<td class="cms_table_grid_td">Rundll32.exe pwlauncher.dll,ShowPortableWorkspaceLauncherConfigurationUX</td>
</tr>
</tbody></table>