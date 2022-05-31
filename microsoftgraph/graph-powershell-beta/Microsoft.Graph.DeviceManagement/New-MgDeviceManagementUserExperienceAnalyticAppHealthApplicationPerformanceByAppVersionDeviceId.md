﻿---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementuserexperienceanalyticapphealthapplicationperformancebyappversiondeviceid
schema: 2.0.0
---

# New-MgDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByAppVersionDeviceId

## SYNOPSIS
User experience analytics appHealth Application Performance by App Version Device Id

## SYNTAX

### CreateExpanded3 (Default)
```
New-MgDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByAppVersionDeviceId
 [-AdditionalProperties <Hashtable>] [-AppCrashCount <Int32>] [-AppDisplayName <String>] [-AppName <String>]
 [-AppPublisher <String>] [-AppVersion <String>] [-DeviceDisplayName <String>] [-DeviceId <String>]
 [-Id <String>] [-ProcessedDateTime <DateTime>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create3
```
New-MgDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByAppVersionDeviceId
 -BodyParameter <IMicrosoftGraphUserExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
User experience analytics appHealth Application Performance by App Version Device Id

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppCrashCount
The number of crashes for the app.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppDisplayName
The friendly name of the application.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppName
The name of the application.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppPublisher
The publisher of the application.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppVersion
The version of the application.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
The user experience analytics application performance entity contains app performance by app version device id.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId
Parameter Sets: Create3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeviceDisplayName
The name of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceId
The id of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProcessedDateTime
The date and time when the statistics were last computed.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId>: The user experience analytics application performance entity contains app performance by app version device id.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AppCrashCount <Int32?>]`: The number of crashes for the app. Valid values -2147483648 to 2147483647
  - `[AppDisplayName <String>]`: The friendly name of the application.
  - `[AppName <String>]`: The name of the application.
  - `[AppPublisher <String>]`: The publisher of the application.
  - `[AppVersion <String>]`: The version of the application.
  - `[DeviceDisplayName <String>]`: The name of the device.
  - `[DeviceId <String>]`: The id of the device.
  - `[ProcessedDateTime <DateTime?>]`: The date and time when the statistics were last computed.

## RELATED LINKS