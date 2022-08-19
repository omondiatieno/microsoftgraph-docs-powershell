---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/update-mgidentitygovernanceaccessreviewdefinitioninstancedecisioninstance
schema: 2.0.0
---

# Update-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInstance

## SYNOPSIS
Update the navigation property instance in identityGovernance

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInstance
 -AccessReviewInstanceDecisionItemId <String> -AccessReviewInstanceId <String>
 -AccessReviewScheduleDefinitionId <String> [-AdditionalProperties <Hashtable>]
 [-ContactedReviewers <IMicrosoftGraphAccessReviewReviewer[]>]
 [-Decisions <IMicrosoftGraphAccessReviewInstanceDecisionItem[]>]
 [-Definition <IMicrosoftGraphAccessReviewScheduleDefinition>] [-EndDateTime <DateTime>]
 [-Errors <IMicrosoftGraphAccessReviewError[]>]
 [-FallbackReviewers <IMicrosoftGraphAccessReviewReviewerScope[]>] [-Id <String>]
 [-Reviewers <IMicrosoftGraphAccessReviewReviewerScope[]>] [-Scope <Hashtable>]
 [-Stages <IMicrosoftGraphAccessReviewStage[]>] [-StartDateTime <DateTime>] [-Status <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInstance
 -AccessReviewInstanceDecisionItemId <String> -AccessReviewInstanceId <String>
 -AccessReviewScheduleDefinitionId <String> -BodyParameter <IMicrosoftGraphAccessReviewInstance> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInstance
 -InputObject <IIdentityGovernanceIdentity> [-AdditionalProperties <Hashtable>]
 [-ContactedReviewers <IMicrosoftGraphAccessReviewReviewer[]>]
 [-Decisions <IMicrosoftGraphAccessReviewInstanceDecisionItem[]>]
 [-Definition <IMicrosoftGraphAccessReviewScheduleDefinition>] [-EndDateTime <DateTime>]
 [-Errors <IMicrosoftGraphAccessReviewError[]>]
 [-FallbackReviewers <IMicrosoftGraphAccessReviewReviewerScope[]>] [-Id <String>]
 [-Reviewers <IMicrosoftGraphAccessReviewReviewerScope[]>] [-Scope <Hashtable>]
 [-Stages <IMicrosoftGraphAccessReviewStage[]>] [-StartDateTime <DateTime>] [-Status <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInstance
 -InputObject <IIdentityGovernanceIdentity> -BodyParameter <IMicrosoftGraphAccessReviewInstance> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property instance in identityGovernance

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AccessReviewInstanceDecisionItemId
key: id of accessReviewInstanceDecisionItem

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AccessReviewInstanceId
key: id of accessReviewInstance

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AccessReviewScheduleDefinitionId
key: id of accessReviewScheduleDefinition

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
accessReviewInstance
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewInstance
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContactedReviewers
Returns the collection of reviewers who were contacted to complete this review.
While the reviewers and fallbackReviewers properties of the accessReviewScheduleDefinition might specify group owners or managers as reviewers, contactedReviewers returns their individual identities.
Supports $select.
Read-only.
To construct, please use Get-Help -Online and see NOTES section for CONTACTEDREVIEWERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewReviewer[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Decisions
Each user reviewed in an accessReviewInstance has a decision item representing if they were approved, denied, or not yet reviewed.
To construct, please use Get-Help -Online and see NOTES section for DECISIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewInstanceDecisionItem[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Definition
accessReviewScheduleDefinition
To construct, please use Get-Help -Online and see NOTES section for DEFINITION properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewScheduleDefinition
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EndDateTime
DateTime when review instance is scheduled to end.The DatetimeOffset type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Supports $select.
Read-only.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Errors
Collection of errors in an access review instance lifecycle.
Read-only.
To construct, please use Get-Help -Online and see NOTES section for ERRORS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewError[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FallbackReviewers
This collection of reviewer scopes is used to define the list of fallback reviewers.
These fallback reviewers will be notified to take action if no users are found from the list of reviewers specified.
This could occur when either the group owner is specified as the reviewer but the group owner does not exist, or manager is specified as reviewer but a user's manager does not exist.
Supports $select.
To construct, please use Get-Help -Online and see NOTES section for FALLBACKREVIEWERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewReviewerScope[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: IIdentityGovernanceIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
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
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Reviewers
This collection of access review scopes is used to define who the reviewers are.
Supports $select.
For examples of options for assigning reviewers, see Assign reviewers to your access review definition using the Microsoft Graph API.
To construct, please use Get-Help -Online and see NOTES section for REVIEWERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewReviewerScope[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Scope
accessReviewScope

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Stages
If the instance has multiple stages, this returns the collection of stages.
A new stage will only be created when the previous stage ends.
The existence, number, and settings of stages on a review instance are created based on the accessReviewStageSettings on the parent accessReviewScheduleDefinition.
To construct, please use Get-Help -Online and see NOTES section for STAGES properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewStage[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTime
DateTime when review instance is scheduled to start.
May be in the future.
The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Supports $select.
Read-only.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Status
Specifies the status of an accessReview.
Possible values: Initializing, NotStarted, Starting, InProgress, Completing, Completed, AutoReviewing, and AutoReviewed.
Supports $select, $orderby, and $filter (eq only).
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IIdentityGovernanceIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAccessReviewInstance
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/update-mgidentitygovernanceaccessreviewdefinitioninstancedecisioninstance](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/update-mgidentitygovernanceaccessreviewdefinitioninstancedecisioninstance)
