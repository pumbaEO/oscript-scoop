A [Scoop](https://github.com/lukesampson/scoop) bucket for Onescript, Spicetify and related packages.

    $ scoop bucket add onescript https://github.com/pumbaEO/oscript-scoop.git

## Installing and customizing Onescript

First, the latest version of Spotify should be installed:

    $ scoop install onescript

Note that Onescript should not be installed globally, as it stores files in user-specific directories.

**If you don't care about reading any of this** and just want a quick way to install Onescript, genius-spicetify and developer tools, copy and paste this into
PowerShell:

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')

scoop install git sudo

scoop bucket add nerd-fonts
sudo scoop install Open-Sans Raleway --global

scoop bucket add spotify hhttps://github.com/pumbaEO/oscript-scoop.git
scoop install onescript


```

**Or even shorter**, but with Adapta-Nokto instead:

I wrote the above script mostly for people who don't care about using Scoop and just need a
foolproof way to set everything up automatically.

And in the future, if you want to update any installed packages:

```powershell
$ scoop update *
```
