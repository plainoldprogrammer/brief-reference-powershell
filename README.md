# Brief Reference PowerShell
Brief reference of PowerShell.

---

#### Delete the current line
```
Ctrl + C
```

#### Change the default theme on the configuration file
```
$ notepad $PROFILE

Change the line:
Set-Theme <theme-name>

NOTE: Must have properly installed "oh-my-posh" module
```

#### List the current theme configuration
```
> $ThemeSettings
```

#### Change the default theme on the current session
```
> Set-Theme <theme-name>

NOTE: Must have properly installed "oh-my-posh" module.
```

#### Get the version of the current powershell
```
> Get-Host | Select-Object Version
```

#### Update the help
```
> Update-Help
```

#### Create a new file
```
> Out-File Program.cs
```

#### Delete a file
```
> Remove-Item Program.cs
```

#### Create a new directory
```
> New-Item -ItemType directory <directory_name>
```

#### Remove a directory recursively
```
> Remove-Item -Recurse -Force <directory_name>
```

#### Display the help of a command
```
> Help <command>
```

#### Move a file into a directory
```
> Move-Item <file> <directory>
```

#### Rename a directory
```
> Rename-Item <old_name> <new_name>
```

#### Execute a program
```
> Start-Process Program.exe
```

#### Show all the files on the current directory
```
> Get-Item *
```

#### Open a new explorer window
```
> explorer
```

#### Open a new explorer window on the current directory location
```
> explorer .
```

#### Generate a file with a list of all files in a directory
```
> Get-ChildItem "C:\Folder" | Select BaseName > C:\Folder\File.txt
```

#### Read a file
```
> Get-Content File.txt
```

#### Recycle the recycle bin
```
> Clear-RecycleBin
```

#### Clear screen
```
> Clear-Host
```

