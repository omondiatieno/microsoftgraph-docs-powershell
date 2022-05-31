﻿---
external help file: Microsoft.Graph.Devices.ServiceAnnouncement-help.xml
Module Name: Microsoft.Graph.Devices.ServiceAnnouncement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.serviceannouncement/new-mgserviceannouncementmessage
schema: 2.0.0
---

# New-MgServiceAnnouncementMessage

## SYNOPSIS
A collection of service messages for tenant.
This property is a contained navigation property, it is nullable and readonly.

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgServiceAnnouncementMessage [-ActionRequiredByDateTime <DateTime>] [-AdditionalProperties <Hashtable>]
 [-Attachments <IMicrosoftGraphServiceAnnouncementAttachment[]>] [-AttachmentsArchiveInputFile <String>]
 [-Body <IMicrosoftGraphItemBody>] [-Category <String>] [-Details <IMicrosoftGraphKeyValuePair[]>]
 [-EndDateTime <DateTime>] [-HasAttachments] [-Id <String>] [-IsMajorChange] [-LastModifiedDateTime <DateTime>]
 [-Services <String[]>] [-Severity <String>] [-StartDateTime <DateTime>] [-Tags <String[]>] [-Title <String>]
 [-ViewPoint <IMicrosoftGraphServiceUpdateMessageViewpoint>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create1
```
New-MgServiceAnnouncementMessage -BodyParameter <IMicrosoftGraphServiceUpdateMessage> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
A collection of service messages for tenant.
This property is a contained navigation property, it is nullable and readonly.

## EXAMPLES

## PARAMETERS

### -ActionRequiredByDateTime
The expected deadline of the action for the message.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Attachments
A collection of serviceAnnouncementAttachments.
To construct, please use Get-Help -Online and see NOTES section for ATTACHMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphServiceAnnouncementAttachment[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttachmentsArchiveInputFile
Input File for AttachmentsArchive (The zip file that contains all attachments for a message.)

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Body
itemBody
To construct, please use Get-Help -Online and see NOTES section for BODY properties and create a hash table.

```yaml
Type: IMicrosoftGraphItemBody
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
serviceUpdateMessage
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphServiceUpdateMessage
Parameter Sets: Create1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Category
serviceUpdateCategory

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Details
Additional details about service event.
This property doesn't support filters.
To construct, please use Get-Help -Online and see NOTES section for DETAILS properties and create a hash table.

```yaml
Type: IMicrosoftGraphKeyValuePair[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EndDateTime
The end time of the service event.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HasAttachments
Indicates whether the message has any attachment.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
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
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsMajorChange
Indicates whether the message describes a major update for the service.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
The last modified time of the service event.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Services
The affected services by the service message.

```yaml
Type: String[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Severity
serviceUpdateSeverity

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTime
The start time of the service event.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tags
A collection of tags for the service message.
Tags are provided by the service team/support team who post the message to tell whether this message contains privacy data, or whether this message is for a service new feature update, and so on.

```yaml
Type: String[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Title
The title of the service event.

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ViewPoint
serviceUpdateMessageViewpoint
To construct, please use Get-Help -Online and see NOTES section for VIEWPOINT properties and create a hash table.

```yaml
Type: IMicrosoftGraphServiceUpdateMessageViewpoint
Parameter Sets: CreateExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphServiceUpdateMessage
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphServiceUpdateMessage
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ATTACHMENTS <IMicrosoftGraphServiceAnnouncementAttachment[]>: A collection of serviceAnnouncementAttachments.
  - `[Id <String>]`: Read-only.
  - `[Content <Byte[]>]`: The attachment content.
  - `[ContentType <String>]`: 
  - `[LastModifiedDateTime <DateTime?>]`: 
  - `[Name <String>]`: 
  - `[Size <Int32?>]`: 

BODY <IMicrosoftGraphItemBody>: itemBody
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Content <String>]`: The content of the item.
  - `[ContentType <String>]`: bodyType

BODYPARAMETER <IMicrosoftGraphServiceUpdateMessage>: serviceUpdateMessage
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Details <IMicrosoftGraphKeyValuePair[]>]`: Additional details about service event. This property doesn't support filters.
    - `[Name <String>]`: Name for this key-value pair
    - `[Value <String>]`: Value for this key-value pair
  - `[EndDateTime <DateTime?>]`: The end time of the service event.
  - `[LastModifiedDateTime <DateTime?>]`: The last modified time of the service event.
  - `[StartDateTime <DateTime?>]`: The start time of the service event.
  - `[Title <String>]`: The title of the service event.
  - `[Id <String>]`: Read-only.
  - `[ActionRequiredByDateTime <DateTime?>]`: The expected deadline of the action for the message.
  - `[Attachments <IMicrosoftGraphServiceAnnouncementAttachment[]>]`: A collection of serviceAnnouncementAttachments.
    - `[Id <String>]`: Read-only.
    - `[Content <Byte[]>]`: The attachment content.
    - `[ContentType <String>]`: 
    - `[LastModifiedDateTime <DateTime?>]`: 
    - `[Name <String>]`: 
    - `[Size <Int32?>]`: 
  - `[AttachmentsArchive <Byte[]>]`: The zip file that contains all attachments for a message.
  - `[Body <IMicrosoftGraphItemBody>]`: itemBody
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Content <String>]`: The content of the item.
    - `[ContentType <String>]`: bodyType
  - `[Category <String>]`: serviceUpdateCategory
  - `[HasAttachments <Boolean?>]`: Indicates whether the message has any attachment.
  - `[IsMajorChange <Boolean?>]`: Indicates whether the message describes a major update for the service.
  - `[Services <String[]>]`: The affected services by the service message.
  - `[Severity <String>]`: serviceUpdateSeverity
  - `[Tags <String[]>]`: A collection of tags for the service message. Tags are provided by the service team/support team who post the message to tell whether this message contains privacy data, or whether this message is for a service new feature update, and so on.
  - `[ViewPoint <IMicrosoftGraphServiceUpdateMessageViewpoint>]`: serviceUpdateMessageViewpoint
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[IsArchived <Boolean?>]`: Indicates whether the user archived the message.
    - `[IsFavorited <Boolean?>]`: Indicates whether the user marked the message as favorite.
    - `[IsRead <Boolean?>]`: Indicates whether the user read the message.

DETAILS <IMicrosoftGraphKeyValuePair[]>: Additional details about service event. This property doesn't support filters.
  - `[Name <String>]`: Name for this key-value pair
  - `[Value <String>]`: Value for this key-value pair

VIEWPOINT <IMicrosoftGraphServiceUpdateMessageViewpoint>: serviceUpdateMessageViewpoint
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[IsArchived <Boolean?>]`: Indicates whether the user archived the message.
  - `[IsFavorited <Boolean?>]`: Indicates whether the user marked the message as favorite.
  - `[IsRead <Boolean?>]`: Indicates whether the user read the message.

## RELATED LINKS