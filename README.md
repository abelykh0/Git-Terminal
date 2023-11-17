# Beautify Your Windows Terminal With posh-git and oh-my-posh
If you use Git then you want to have some visual information when you make changes in your terminal.

![image](https://github.com/abelykh0/Git-Terminal/assets/11560318/3de64fef-dda2-4889-aebb-32ef05568840)

## Install Windows Terminal
```
winget install Microsoft.WindowsTerminal
```

## Install PowerShell 7 64 bit
```
winget install Microsoft.Powershell
```

## Install oh-my-posh
```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

## Install posh-git
Start the PowerShell as an Administrator
```
Install-Module posh-git -Scope CurrentUser
```

## Save the Profile
```
notepad $PROFILE
```
```
Import-Module posh-git
oh-my-posh init pwsh | Invoke-Expression
```

## Install the Fonts
```
oh-my-posh font install
```
Select `CascadiaCode`

## Change Windows Terminal Settings

![image](https://github.com/abelykh0/Git-Terminal/assets/11560318/e425cd05-c969-445f-8d82-ec3467e53930)

![image](https://github.com/abelykh0/Git-Terminal/assets/11560318/83667d38-4820-4293-b9bc-6ed80ce9ae9f)

## Links:
https://github.com/dahlbyk/posh-git

https://ohmyposh.dev/

https://anshbadaya.medium.com/customizing-windows-terminal-with-posh-git-and-oh-my-posh-752c0e0eb8cb

https://ohmyposh.dev/docs/installation/fonts

https://www.hanselman.com/blog/how-to-make-a-pretty-prompt-in-windows-terminal-with-powerline-nerd-fonts-cascadia-code-wsl-and-ohmyposh

