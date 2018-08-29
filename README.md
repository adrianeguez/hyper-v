# hyper-v

## 

https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/connect-to-network
```  
$ Get-NetAdapter
$ $net = Get-NetAdapter -Name 'Ethernet'
$ New-VMSwitch -Name "External VM Switch" -AllowManagementOS $True -NetAdapterName $net.Name
```

