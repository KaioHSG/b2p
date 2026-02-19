``` powershell
irm "kaiohsg.dev/b2p/get.ps1" | iex
```

``` powershell
iex "& { $(irm 'kaiohsg.dev/b2p/get.ps1') } -UpdatePath"
```
