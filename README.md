## Using Classic Control Panel On Windows 11

#### Opening Control Panel:
```ps1
control.exe
```

#### Canonical way of opening Add Remove Programs (ARP):
```ps1
control.exe appwiz.cpl
```

#### Alternative 1, that do the same thing:
```ps1
control appwiz.cpl
```

#### Alternative 2, that do the same thing:
```ps1
appwiz.cpl
```

#### If you want to run it from PowerShell or a script:
```ps1
Start-Process appwiz.cpl
```

