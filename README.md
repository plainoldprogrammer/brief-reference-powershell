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
