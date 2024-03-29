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

#### Display the help of a command
```
> Get-Help <command>
```

#### Display a list of commands that supports get operation
```
> Get-Command Get-*
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
> New-Item -ItemType Directory <directory_name>
```

#### Remove a directory recursively
```
> Remove-Item -Recurse -Force <directory_name>
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

#### Get a full list of available commands
```
> Get-Command
```

#### Set a location
```
> Set-Location -Path "C:\Users\"
```

#### Add content to a specific file
```
> Add-Content	<file>
```

#### Pass the object from a cmdlet to another cmdlet
```
> Get-ChildItem | Format-List
```

#### Define a variable
```
> $A = Get-ChildItem
```

#### Unassign a variable
```
> $A = ""
```

#### Get a list of the processes
```
> Get-Process
```

#### Get all services that begin with "xb"
```
> Get-Service "vm*"
```

#### Convert the output of a cmdlet into html
```
> Get-ChildItem | ConvertTo-Html
```

#### Get the current date
```
> Get-Date
```
