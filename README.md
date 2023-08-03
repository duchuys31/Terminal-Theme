### Fonts
- Download fonts: https://github.com/ryanoasis/nerd-fonts/releases/tag/v2.1.0
### Enter each command into the terminal
- iwr -useb get.scoop.sh | iex 
- winget install -e --id Git.Git
- scoop install neovim gcc
- Install-Module posh-git -Scope CurrentUser -Force
- winget install JanDeDobbeleer.OhMyPosh -s winget
- exit
- mkdir .config/powershell
- cd /config/powershell
- nvim users_profile.ps1 (paste)
- nvim $PROFILE.CurrentUserCurrentHost( paste '. $env:USERPROFILE\.config\powershell\uers_profile.ps1' )
- nvim users.omp.json (paste)
