# paradox-cascadia

A derivative of the Paradox PowerShell theme included in [oh-my-posh V2](https://github.com/JanDeDobbeleer/oh-my-posh), modified to be compatible with the [Cascadia Code PL](https://github.com/microsoft/cascadia-code) font. As of February 2021, the Cascadia Code PL font is missing some key Nerd Font icons that the standard Paradox theme relies on, specifically the symbols for elevation, failed commands, and virtual environments. In this derivative the missing symbols are instead replaced with `SUDO`, `ERR`, and `ENV` respectively.

## Setup

1. Install [posh-git](https://github.com/dahlbyk/posh-git) and [oh-my-posh V2](https://github.com/JanDeDobbeleer/oh-my-posh)
2. Download `paradox-cascadia.psm1` and place into `PoshThemes` within your PowerShell configuration folder
    - PowerShell Core: `~\Documents\PowerShell\PoshThemes\paradox-cascadia.psm1`
    - Windows PowerShell: `~\Documents\WindowsPowerShell\PoshThemes\paradox-cascadia.psm1`
3. Place the following lines into your PowerShell profile:
    ```powershell
    Import-Module posh-git
    Import-Module oh-my-posh
    Set-Theme paradox-cascadia
    ```
