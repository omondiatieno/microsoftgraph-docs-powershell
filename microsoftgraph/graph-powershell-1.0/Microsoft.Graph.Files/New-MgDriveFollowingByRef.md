﻿---
external help file: Microsoft.Graph.Files-help.xml
Module Name: Microsoft.Graph.Files
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.files/new-mgdrivefollowingbyref
schema: 2.0.0
---

# New-MgDriveFollowingByRef

## SYNOPSIS
The list of items the user is following.
Only in OneDrive for Business.

## SYNTAX

<<<<<<< HEAD
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
### CreateExpanded (Default)
```
New-MgDriveFollowingByRef -DriveId <String> [-AdditionalProperties <Hashtable>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Create
```
New-MgDriveFollowingByRef -DriveId <String> -BodyParameter <Hashtable> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
=======
>>>>>>> live
### CreateExpanded1 (Default)
```
New-MgDriveFollowingByRef -DriveId <String> [-AdditionalProperties <Hashtable>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Create1
```
New-MgDriveFollowingByRef -DriveId <String> -BodyParameter <Hashtable> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
<<<<<<< HEAD
=======
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
New-MgDriveFollowingByRef -InputObject <IFilesIdentity> [-AdditionalProperties <Hashtable>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

<<<<<<< HEAD
### CreateViaIdentity1
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
### CreateViaIdentity
=======
### CreateViaIdentity1
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
```
New-MgDriveFollowingByRef -InputObject <IFilesIdentity> -BodyParameter <Hashtable> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The list of items the user is following.
Only in OneDrive for Business.

## EXAMPLES

<<<<<<< HEAD
=======
### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

>>>>>>> live
## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
<<<<<<< HEAD
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
=======
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.

```yaml
Type: Hashtable
<<<<<<< HEAD
Parameter Sets: Create1, CreateViaIdentity1
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
Parameter Sets: Create, CreateViaIdentity
=======
Parameter Sets: Create1, CreateViaIdentity1
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DriveId
key: id of drive

```yaml
Type: String
<<<<<<< HEAD
Parameter Sets: CreateExpanded1, Create1
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
Parameter Sets: CreateExpanded, Create
=======
Parameter Sets: CreateExpanded1, Create1
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
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
Type: IFilesIdentity
<<<<<<< HEAD
Parameter Sets: CreateViaIdentityExpanded1, CreateViaIdentity1
=======
<<<<<<< HEAD:microsoftgraph/graph-powershell-beta/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
=======
Parameter Sets: CreateViaIdentityExpanded1, CreateViaIdentity1
>>>>>>> live:microsoftgraph/graph-powershell-1.0/Microsoft.Graph.Files/New-MgDriveFollowingByRef.md
>>>>>>> live
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### Microsoft.Graph.PowerShell.Models.IFilesIdentity
### System.Collections.Hashtable
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IPathsLayc76DrivesDriveIdFollowingRefPostResponses201ContentApplicationJsonSchema
## NOTES
<<<<<<< HEAD

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IFilesIdentity>: Identity Parameter
  - `[ColumnDefinitionId <String>]`: key: id of columnDefinition
  - `[ColumnLinkId <String>]`: key: id of columnLink
  - `[ContentTypeId <String>]`: key: id of contentType
  - `[DriveId <String>]`: key: id of drive
  - `[DriveItemId <String>]`: key: id of driveItem
  - `[EndDateTime <String>]`: Usage: endDateTime={endDateTime}
  - `[GroupId <String>]`: key: id of group
  - `[Interval <String>]`: Usage: interval={interval}
  - `[ListItemId <String>]`: key: id of listItem
  - `[ListItemVersionId <String>]`: key: id of listItemVersion
  - `[Q <String>]`: Usage: q={q}
  - `[RichLongRunningOperationId <String>]`: key: id of richLongRunningOperation
  - `[SharedDriveItemId <String>]`: key: id of sharedDriveItem
  - `[StartDateTime <String>]`: Usage: startDateTime={startDateTime}
  - `[SubscriptionId <String>]`: key: id of subscription
  - `[Token <String>]`: Usage: token={token}
  - `[UserId <String>]`: key: id of user

## RELATED LINKS
=======
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.files/new-mgdrivefollowingbyref](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.files/new-mgdrivefollowingbyref)

>>>>>>> live