# Oh-My-Posh
Personal Oh My Posh configuration.

## Install Oh-My-Posh

Open a PowerShell prompt and run the following command:

```powershell
winget install JanDeDobbeleer.OhMyPosh -s winget
```

## Configure

Edit the PowerShell profile file to load the configuration file

```powershell
$omp_config = 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/jandedobbeleer.omp.json'
oh-my-posh --init --shell pwsh --config $omp_config | Invoke-Expression =
```
