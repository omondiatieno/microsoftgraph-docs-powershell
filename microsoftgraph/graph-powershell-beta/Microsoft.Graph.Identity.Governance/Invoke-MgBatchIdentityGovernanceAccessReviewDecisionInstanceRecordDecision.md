﻿---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/invoke-mgbatchidentitygovernanceaccessreviewdecisioninstancerecorddecision
schema: 2.0.0
---

# Invoke-MgBatchIdentityGovernanceAccessReviewDecisionInstanceRecordDecision

## SYNOPSIS
Invoke action batchRecordDecisions

## SYNTAX

### BatchExpanded (Default)
```
Invoke-MgBatchIdentityGovernanceAccessReviewDecisionInstanceRecordDecision
 -AccessReviewInstanceDecisionItemId <String> [-AdditionalProperties <Hashtable>] [-Decision <String>]
 [-Justification <String>] [-PrincipalId <String>] [-ResourceId <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Batch
```
Invoke-MgBatchIdentityGovernanceAccessReviewDecisionInstanceRecordDecision
 -AccessReviewInstanceDecisionItemId <String>
 -BodyParameter <IPaths1Qw0RdiIdentitygovernanceAccessreviewsDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### BatchViaIdentityExpanded
```
Invoke-MgBatchIdentityGovernanceAccessReviewDecisionInstanceRecordDecision
 -InputObject <IIdentityGovernanceIdentity> [-AdditionalProperties <Hashtable>] [-Decision <String>]
 [-Justification <String>] [-PrincipalId <String>] [-ResourceId <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### BatchViaIdentity
```
Invoke-MgBatchIdentityGovernanceAccessReviewDecisionInstanceRecordDecision
 -InputObject <IIdentityGovernanceIdentity>
 -BodyParameter <IPaths1Qw0RdiIdentitygovernanceAccessreviewsDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action batchRecordDecisions

## EXAMPLES

## PARAMETERS

### -AccessReviewInstanceDecisionItemId
key: id of accessReviewInstanceDecisionItem

```yaml
Type: String
Parameter Sets: BatchExpanded, Batch
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
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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
Type: IPaths1Qw0RdiIdentitygovernanceAccessreviewsDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Batch, BatchViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Decision
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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
Parameter Sets: BatchViaIdentityExpanded, BatchViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Justification
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
Aliases:

Required: False
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
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrincipalId
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceId
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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
### Microsoft.Graph.PowerShell.Models.IPaths1Qw0RdiIdentitygovernanceAccessreviewsDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPaths1Qw0RdiIdentitygovernanceAccessreviewsDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Decision <String>]`: 
  - `[Justification <String>]`: 
  - `[PrincipalId <String>]`: 
  - `[ResourceId <String>]`: 

INPUTOBJECT <IIdentityGovernanceIdentity>: Identity Parameter
  - `[AccessPackageAssignmentId <String>]`: key: id of accessPackageAssignment
  - `[AccessPackageAssignmentPolicyId <String>]`: key: id of accessPackageAssignmentPolicy
  - `[AccessPackageAssignmentRequestId <String>]`: key: id of accessPackageAssignmentRequest
  - `[AccessPackageAssignmentResourceRoleId <String>]`: key: id of accessPackageAssignmentResourceRole
  - `[AccessPackageCatalogId <String>]`: key: id of accessPackageCatalog
  - `[AccessPackageId <String>]`: key: id of accessPackage
  - `[AccessPackageResourceEnvironmentId <String>]`: key: id of accessPackageResourceEnvironment
  - `[AccessPackageResourceId <String>]`: key: id of accessPackageResource
  - `[AccessPackageResourceRequestId <String>]`: key: id of accessPackageResourceRequest
  - `[AccessPackageResourceRoleId <String>]`: key: id of accessPackageResourceRole
  - `[AccessPackageResourceRoleScopeId <String>]`: key: id of accessPackageResourceRoleScope
  - `[AccessPackageResourceScopeId <String>]`: key: id of accessPackageResourceScope
  - `[AccessReviewDecisionId <String>]`: key: id of accessReviewDecision
  - `[AccessReviewHistoryDefinitionId <String>]`: key: id of accessReviewHistoryDefinition
  - `[AccessReviewHistoryInstanceId <String>]`: key: id of accessReviewHistoryInstance
  - `[AccessReviewId <String>]`: key: id of accessReview
  - `[AccessReviewId1 <String>]`: key: id of accessReview
  - `[AccessReviewInstanceDecisionItemId <String>]`: key: id of accessReviewInstanceDecisionItem
  - `[AccessReviewInstanceDecisionItemId1 <String>]`: key: id of accessReviewInstanceDecisionItem
  - `[AccessReviewInstanceId <String>]`: key: id of accessReviewInstance
  - `[AccessReviewReviewerId <String>]`: key: id of accessReviewReviewer
  - `[AccessReviewScheduleDefinitionId <String>]`: key: id of accessReviewScheduleDefinition
  - `[AccessReviewStageId <String>]`: key: id of accessReviewStage
  - `[AgreementAcceptanceId <String>]`: key: id of agreementAcceptance
  - `[AgreementFileLocalizationId <String>]`: key: id of agreementFileLocalization
  - `[AgreementFileVersionId <String>]`: key: id of agreementFileVersion
  - `[AgreementId <String>]`: key: id of agreement
  - `[AppConsentRequestId <String>]`: key: id of appConsentRequest
  - `[ApprovalId <String>]`: key: id of approval
  - `[ApprovalStageId <String>]`: key: id of approvalStage
  - `[ApprovalStepId <String>]`: key: id of approvalStep
  - `[BusinessFlowTemplateId <String>]`: key: id of businessFlowTemplate
  - `[ConnectedOrganizationId <String>]`: key: id of connectedOrganization
  - `[CustomAccessPackageWorkflowExtensionId <String>]`: key: id of customAccessPackageWorkflowExtension
  - `[CustomExtensionHandlerId <String>]`: key: id of customExtensionHandler
  - `[DirectoryObjectId <String>]`: key: id of directoryObject
  - `[GovernanceInsightId <String>]`: key: id of governanceInsight
  - `[GovernanceResourceId <String>]`: key: id of governanceResource
  - `[GovernanceRoleAssignmentId <String>]`: key: id of governanceRoleAssignment
  - `[GovernanceRoleAssignmentRequestId <String>]`: key: id of governanceRoleAssignmentRequest
  - `[GovernanceRoleDefinitionId <String>]`: key: id of governanceRoleDefinition
  - `[GovernanceRoleSettingId <String>]`: key: id of governanceRoleSetting
  - `[On <String>]`: Usage: on={on}
  - `[PrivilegedAccessId <String>]`: key: id of privilegedAccess
  - `[PrivilegedApprovalId <String>]`: key: id of privilegedApproval
  - `[PrivilegedOperationEventId <String>]`: key: id of privilegedOperationEvent
  - `[PrivilegedRoleAssignmentId <String>]`: key: id of privilegedRoleAssignment
  - `[PrivilegedRoleAssignmentRequestId <String>]`: key: id of privilegedRoleAssignmentRequest
  - `[PrivilegedRoleId <String>]`: key: id of privilegedRole
  - `[ProgramControlId <String>]`: key: id of programControl
  - `[ProgramControlTypeId <String>]`: key: id of programControlType
  - `[ProgramId <String>]`: key: id of program
  - `[UserConsentRequestId <String>]`: key: id of userConsentRequest
  - `[UserId <String>]`: key: id of user

## RELATED LINKS