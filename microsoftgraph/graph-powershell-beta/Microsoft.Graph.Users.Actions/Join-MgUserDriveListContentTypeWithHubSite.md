---
external help file: Microsoft.Graph.Users.Actions-help.xml
Module Name: Microsoft.Graph.Users.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/join-mguserdrivelistcontenttypewithhubsite
schema: 2.0.0
---

# Join-MgUserDriveListContentTypeWithHubSite

## SYNOPSIS
Invoke action associateWithHubSites

## SYNTAX

### AssociateExpanded1 (Default)
```
Join-MgUserDriveListContentTypeWithHubSite -ContentTypeId <String> -DriveId <String> -UserId <String>
 [-AdditionalProperties <Hashtable>] [-HubSiteUrls <String[]>] [-PropagateToExistingLists] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Associate1
```
Join-MgUserDriveListContentTypeWithHubSite -ContentTypeId <String> -DriveId <String> -UserId <String>
 -BodyParameter <IPaths7Q2KgfUsersUserIdDrivesDriveIdListContenttypesContenttypeIdMicrosoftGraphAssociatewithhubsitesPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AssociateViaIdentityExpanded1
```
Join-MgUserDriveListContentTypeWithHubSite -InputObject <IUsersActionsIdentity>
 [-AdditionalProperties <Hashtable>] [-HubSiteUrls <String[]>] [-PropagateToExistingLists] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AssociateViaIdentity1
```
Join-MgUserDriveListContentTypeWithHubSite -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPaths7Q2KgfUsersUserIdDrivesDriveIdListContenttypesContenttypeIdMicrosoftGraphAssociatewithhubsitesPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action associateWithHubSites

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: AssociateExpanded1, AssociateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPaths7Q2KgfUsersUserIdDrivesDriveIdListContenttypesContenttypeIdMicrosoftGraphAssociatewithhubsitesPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Associate1, AssociateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContentTypeId
key: id of contentType

```yaml
Type: String
Parameter Sets: AssociateExpanded1, Associate1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DriveId
key: id of drive

```yaml
Type: String
Parameter Sets: AssociateExpanded1, Associate1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HubSiteUrls
.

```yaml
Type: String[]
Parameter Sets: AssociateExpanded1, AssociateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IUsersActionsIdentity
Parameter Sets: AssociateViaIdentityExpanded1, AssociateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PropagateToExistingLists
.

```yaml
Type: SwitchParameter
Parameter Sets: AssociateExpanded1, AssociateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
key: id of user

```yaml
Type: String
Parameter Sets: AssociateExpanded1, Associate1
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IPaths7Q2KgfUsersUserIdDrivesDriveIdListContenttypesContenttypeIdMicrosoftGraphAssociatewithhubsitesPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPaths7Q2KgfUsersUserIdDrivesDriveIdListContenttypesContenttypeIdMicrosoftGraphAssociatewithhubsitesPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[HubSiteUrls <String[]>]`: 
  - `[PropagateToExistingLists <Boolean?>]`: 

INPUTOBJECT `<IUsersActionsIdentity>`: Identity Parameter
  - `[AccessReviewInstanceId <String>]`: key: id of accessReviewInstance
  - `[AccessReviewStageId <String>]`: key: id of accessReviewStage
  - `[AppLogCollectionRequestId <String>]`: key: id of appLogCollectionRequest
  - `[AuthenticationMethodId <String>]`: key: id of authenticationMethod
  - `[BaseTaskId <String>]`: key: id of baseTask
  - `[BaseTaskListId <String>]`: key: id of baseTaskList
  - `[CalendarId <String>]`: key: id of calendar
  - `[ChatId <String>]`: key: id of chat
  - `[ChatMessageId <String>]`: key: id of chatMessage
  - `[ChatMessageId1 <String>]`: key: id of chatMessage
  - `[CloudPcId <String>]`: key: id of cloudPC
  - `[ContentTypeId <String>]`: key: id of contentType
  - `[DeviceEnrollmentConfigurationId <String>]`: key: id of deviceEnrollmentConfiguration
  - `[DeviceId <String>]`: key: id of device
  - `[DeviceLogCollectionResponseId <String>]`: key: id of deviceLogCollectionResponse
  - `[DocumentSetVersionId <String>]`: key: id of documentSetVersion
  - `[DriveId <String>]`: key: id of drive
  - `[DriveItemId <String>]`: key: id of driveItem
  - `[DriveItemVersionId <String>]`: key: id of driveItemVersion
  - `[EventId <String>]`: key: id of event
  - `[EventId1 <String>]`: key: id of event
  - `[ListItemId <String>]`: key: id of listItem
  - `[ListItemVersionId <String>]`: key: id of listItemVersion
  - `[MailFolderId <String>]`: key: id of mailFolder
  - `[MailFolderId1 <String>]`: key: id of mailFolder
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[MessageId <String>]`: key: id of message
  - `[MicrosoftAuthenticatorAuthenticationMethodId <String>]`: key: id of microsoftAuthenticatorAuthenticationMethod
  - `[MobileAppTroubleshootingEventId <String>]`: key: id of mobileAppTroubleshootingEvent
  - `[NotebookId <String>]`: key: id of notebook
  - `[OnenotePageId <String>]`: key: id of onenotePage
  - `[OnenoteSectionId <String>]`: key: id of onenoteSection
  - `[OutlookTaskFolderId <String>]`: key: id of outlookTaskFolder
  - `[OutlookTaskGroupId <String>]`: key: id of outlookTaskGroup
  - `[OutlookTaskId <String>]`: key: id of outlookTask
  - `[PasswordlessMicrosoftAuthenticatorAuthenticationMethodId <String>]`: key: id of passwordlessMicrosoftAuthenticatorAuthenticationMethod
  - `[PermissionId <String>]`: key: id of permission
  - `[ResourceSpecificPermissionGrantId <String>]`: key: id of resourceSpecificPermissionGrant
  - `[SensitivityLabelId <String>]`: key: id of sensitivityLabel
  - `[SubscriptionId <String>]`: key: id of subscription
  - `[TeamsAppInstallationId <String>]`: key: id of teamsAppInstallation
  - `[TodoTaskId <String>]`: key: id of todoTask
  - `[TodoTaskListId <String>]`: key: id of todoTaskList
  - `[UserId <String>]`: key: id of user
  - `[WindowsHelloForBusinessAuthenticationMethodId <String>]`: key: id of windowsHelloForBusinessAuthenticationMethod

## RELATED LINKS