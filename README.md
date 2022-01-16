✅Most useful Reg keys:
-------------------------------------------------------------------------------------------------------------------------
☸Run/RunOnce keys
User Level-
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Run
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\RunOnce
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\RunOnceEx
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\RunServices
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\N\RunServicesOnce
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\Run
HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Windows\CurrentVersion\Run


HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunOnce
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunOnceEx
HKEY_CURRENT_USER\Software\Microsoft\WindowsNT\CurrentVersion\Windows\Run
HKEY_LOCAL_MACHINE\SYSTEM\ControlSetXXX\Control\Session Manager

☸System Level-
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run

☸BootExecute key-
userinit key- HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon
HKEY_LOCAL_MACHINE\SYSTEM\ControlSetXXX\Control\Session Manager

The following registry values, under their respective registry key, will trigger execution when any user logs in:
HKEY_CURRENT_USER\Software\Microsoft\WindowsNT\CurrentVersion\Windows
HKEY_LOCAL_MACHINE\SYSTEM\ControlSetXXX\Control\Session Manager
XXX in ControlSetXXX is a three digit number usually ControlSet001, ControlSet002, or ControlSet003.

BootExecute = <file path>
The default value of BootExecute is autocheck autochk * Winlogon key
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\Winlogon

Notify Key- HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Notify
Explorer.exe- HKEY_LOCAL_MACHINE\SOFTWARE\MicrosoftWindows NT\CurrentVersion\Winlogon\Shell

☸Startup Keys-
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Shell Folders
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell

☸Start background services- 
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\RunServicesOnce

☸Browser Helper Objects-
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Browser Helper Objects

☸AppInit_DLLs-
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows\AppInit_DLLs

☸File Association Keys-
HKEY_LOCAL_MACHINE\Software\Classes
HKEY_CLASSES_ROOT
  
☸Policy scripts keys
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Group Policy\Scripts\Shutdown\0\N 
where N is a number starting from 0. Multiple scripts orexecutables can be run during the shutdown sequence Script = [file path of executable file or script]
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Group Policy\Scripts\Startup\0\N
