# lern-hyper-v
lerning hyper-v

## get date

```powershell
echo "AppServer_$((Get-Date).toshortdatestring())"
```

## backup 

```powershell
Checkpoint-VM -Name Test -SnapshotName mySnapshotName_$((Get-Date).toshortdatestring())
```

