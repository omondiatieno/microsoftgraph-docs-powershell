---
external help file: Microsoft.Graph.Security-help.xml
Module Name: Microsoft.Graph.Security
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/new-mgsecuritycaseediscoverycasesearchadditionalsource
schema: 2.0.0
---

# New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource

## SYNOPSIS
Create new navigation property to additionalSources for security

## SYNTAX

### CreateExpanded (Default)
```
New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource -EdiscoveryCaseId <String> -EdiscoverySearchId <String>
 [-AdditionalProperties <Hashtable>] [-CreatedBy <IMicrosoftGraphIdentitySet>] [-CreatedDateTime <DateTime>]
 [-DisplayName <String>] [-HoldStatus <String>] [-Id <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource -EdiscoveryCaseId <String> -EdiscoverySearchId <String>
 -BodyParameter <IMicrosoftGraphSecurityDataSource> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource -InputObject <ISecurityIdentity>
 [-AdditionalProperties <Hashtable>] [-CreatedBy <IMicrosoftGraphIdentitySet>] [-CreatedDateTime <DateTime>]
 [-DisplayName <String>] [-HoldStatus <String>] [-Id <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource -InputObject <ISecurityIdentity>
 -BodyParameter <IMicrosoftGraphSecurityDataSource> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to additionalSources for security

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
dataSource
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphSecurityDataSource
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedBy
identitySet
To construct, please use Get-Help -Online and see NOTES section for CREATEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentitySet
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The date and time the dataSource was created.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The display name of the dataSource.
This will be the name of the SharePoint site.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EdiscoveryCaseId
key: id of ediscoveryCase

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EdiscoverySearchId
key: id of ediscoverySearch

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HoldStatus
dataSourceHoldStatus

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: ISecurityIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSecurityDataSource
### Microsoft.Graph.PowerShell.Models.ISecurityIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSecurityDataSource
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IMicrosoftGraphSecurityDataSource>`: dataSource
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: 
  - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Application <IMicrosoftGraphIdentity>]`: identity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      - `[Id <String>]`: Unique identifier for the identity.
    - `[Device <IMicrosoftGraphIdentity>]`: identity
    - `[User <IMicrosoftGraphIdentity>]`: identity
  - `[CreatedDateTime <DateTime?>]`: The date and time the dataSource was created.
  - `[DisplayName <String>]`: The display name of the dataSource. This will be the name of the SharePoint site.
  - `[HoldStatus <String>]`: dataSourceHoldStatus

CREATEDBY `<IMicrosoftGraphIdentitySet>`: identitySet
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Application <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
  - `[Device <IMicrosoftGraphIdentity>]`: identity
  - `[User <IMicrosoftGraphIdentity>]`: identity

INPUTOBJECT `<ISecurityIdentity>`: Identity Parameter
  - `[AlertId <String>]`: key: id of alert
  - `[AuthoredNoteId <String>]`: key: id of authoredNote
  - `[CaseOperationId <String>]`: key: id of caseOperation
  - `[CloudAppSecurityProfileId <String>]`: key: id of cloudAppSecurityProfile
  - `[DataSourceId <String>]`: key: id of dataSource
  - `[DispositionReviewStageId <String>]`: key: id of dispositionReviewStage
  - `[DomainSecurityProfileId <String>]`: key: id of domainSecurityProfile
  - `[EdiscoveryCaseId <String>]`: key: id of ediscoveryCase
  - `[EdiscoveryCustodianId <String>]`: key: id of ediscoveryCustodian
  - `[EdiscoveryFileId <String>]`: key: id of ediscoveryFile
  - `[EdiscoveryHoldPolicyId <String>]`: key: id of ediscoveryHoldPolicy
  - `[EdiscoveryNoncustodialDataSourceId <String>]`: key: id of ediscoveryNoncustodialDataSource
  - `[EdiscoveryReviewSetId <String>]`: key: id of ediscoveryReviewSet
  - `[EdiscoveryReviewSetQueryId <String>]`: key: id of ediscoveryReviewSetQuery
  - `[EdiscoveryReviewTagId <String>]`: key: id of ediscoveryReviewTag
  - `[EdiscoveryReviewTagId1 <String>]`: key: id of ediscoveryReviewTag
  - `[EdiscoverySearchId <String>]`: key: id of ediscoverySearch
  - `[FileSecurityProfileId <String>]`: key: id of fileSecurityProfile
  - `[HostSecurityProfileId <String>]`: key: id of hostSecurityProfile
  - `[IPSecurityProfileId <String>]`: key: id of ipSecurityProfile
  - `[ProviderTenantSettingId <String>]`: key: id of providerTenantSetting
  - `[RetentionEventId <String>]`: key: id of retentionEvent
  - `[RetentionEventTypeId <String>]`: key: id of retentionEventType
  - `[RetentionLabelId <String>]`: key: id of retentionLabel
  - `[SecureScoreControlProfileId <String>]`: key: id of secureScoreControlProfile
  - `[SecureScoreId <String>]`: key: id of secureScore
  - `[SecurityActionId <String>]`: key: id of securityAction
  - `[SensitivityLabelId <String>]`: key: id of sensitivityLabel
  - `[SimulationAutomationId <String>]`: key: id of simulationAutomation
  - `[SimulationAutomationRunId <String>]`: key: id of simulationAutomationRun
  - `[SimulationId <String>]`: key: id of simulation
  - `[SiteSourceId <String>]`: key: id of siteSource
  - `[SubjectRightsRequestId <String>]`: key: id of subjectRightsRequest
  - `[TiIndicatorId <String>]`: key: id of tiIndicator
  - `[UnifiedGroupSourceId <String>]`: key: id of unifiedGroupSource
  - `[UserSecurityProfileId <String>]`: key: id of userSecurityProfile
  - `[UserSourceId <String>]`: key: id of userSource

## RELATED LINKS