# windows-terminal-settings

## Installation
### Dependencies
* Windows terminal, available from the windows store.
* Cascadia Code PL,  available as part of the [Cascadia Code](https://github.com/microsoft/cascadia-code) release. 


### Install Instructions
Not tested yet:
```
git clone https://github.com/hesnotaveryniceman/windows-terminal-settings
cd windows-terminal-settings
copy C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json.bak
rmdir C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
mklink /H C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json settings.json
```
