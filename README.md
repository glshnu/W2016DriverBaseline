"# W2016DriverBaseline"

This powershell script read all installed drivers with version to a csv file.

#Get driver baseline in windows powershell
```powershell
Get-WmiObject Win32_PnPSignedDriver| select devicename, driverversion | Export-Csv -Path c:\server.csv
```

If you have questions send me a mail to lauer(AT)glsh(point)net
