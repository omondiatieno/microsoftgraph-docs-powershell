---
external help file: Microsoft.Graph.DeviceManagement.Functions-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Functions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.functions/get-mgdevicemanagementvirtualendpointreportrealtimeremoteconnectionstatus
schema: 2.0.0
---

# Get-MgDeviceManagementVirtualEndpointReportRealTimeRemoteConnectionStatus

## SYNOPSIS
Invoke function getRealTimeRemoteConnectionStatus

## SYNTAX

### Get (Default)
```
Get-MgDeviceManagementVirtualEndpointReportRealTimeRemoteConnectionStatus -CloudPcId <String> -OutFile <String>
 [-PassThru] [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgDeviceManagementVirtualEndpointReportRealTimeRemoteConnectionStatus
 -InputObject <IDeviceManagementFunctionsIdentity> -OutFile <String> [-PassThru] [<CommonParameters>]
```

## DESCRIPTION
Invoke function getRealTimeRemoteConnectionStatus

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -CloudPcId
Usage: cloudPcId='{cloudPcId}'

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementFunctionsIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OutFile
Path to write output file to

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IDeviceManagementFunctionsIdentity
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.functions/get-mgdevicemanagementvirtualendpointreportrealtimeremoteconnectionstatus](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.functions/get-mgdevicemanagementvirtualendpointreportrealtimeremoteconnectionstatus)
