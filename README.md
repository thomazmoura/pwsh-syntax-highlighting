# pwsh-syntax-highlighting
This project is inspired by the [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting "Fish shell like syntax highlighting for Zsh") project

*Requirement: pwsh 5.1+*

This package provides syntax highlighting for PowerShell. 
It enables highlighting of commands whilst they are typed at a PowerShell prompt into an interactive terminal. 
This helps in reviewing commands before running them, particularly in catching syntax errors.

## Preview

![preview](https://urlzs.com/fiWmK)

## How to install

1. Run PowerShell as Administrator.

2. Execute the following command:

    ```pwsh
    Install-Module syntax-highlighting
    ```
 
3. Restart PowerShell and run:

   ```pwsh
   Import-Module syntax-highlighting
   ```
   
   or simply:
   
   ```pwsh
   echo "Import-Module syntax-highlighting" >> $profile
   ```
   
   so you don't have to import the module every time you open PowerShell.
   
 ## Limitations
 
- Command validation will only after pressing the spacebar
- Second line commands will not be validated 
- Only works with Windows and doesn't work on macOS/Linux
- Doesn't fully support all oh-my-posh themes
  
| Theme  | Full Support |
| ------------- | ------------- |
| agnoster  | ✅  |
| agnosterplus  | ✅  |
| aliens  | ✅  |
| amro  | ✅  |
| atomic  | ✅  |
| atomicBit  | ✅  |
| avit  | ✅  |
| blueish  | ✅  |
| blue-owl  | ✅  |
| bubbles  | ✅  |
| bubblesextra  | ✅  |
| bubblesline  | ✅  |
| capr4n  | ❌  |
| cert  | ✅  |
| cinnamon  | ✅  |
| clean-detailed  | ✅  |
| cloud-native-azure  | ❌  |
| craver  | ✅  |
| darkblood  | ✅  |
| default  | ✅  |
| di4am0nd  | ❌  |
| dracula  | ✅  |
| emodipt  | ✅  |
| festivetech  | ✅  |
