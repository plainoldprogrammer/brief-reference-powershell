# Brief Reference PowerShell
Brief reference of PowerShell.

---

#### List the current theme configuration
```
> $ThemeSettings
```

#### Change the default theme on the configuration file
```
$ notepad $PROFILE

Change the line:
Set-Theme <theme-name>

NOTE: Must have properly installed "oh-my-posh" module
```

#### Change the default theme on the current session
```
$ Set-Theme <theme-name>

NOTE: Must have properly installed "oh-my-posh" module.
```

#### Delete the current line
```
Ctrl + C
```

#### Get the version of the current powershell
```
> Get-Host | Select-Object Version
```

#### Create a new file
```
> Out-File Program.cs
```

#### Delete a file
```
> Remove-Item Program.cs
```
