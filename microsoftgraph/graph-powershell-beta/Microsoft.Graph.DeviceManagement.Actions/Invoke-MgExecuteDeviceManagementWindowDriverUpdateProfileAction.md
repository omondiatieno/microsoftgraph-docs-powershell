﻿---
external help file: Microsoft.Graph.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/invoke-mgexecutedevicemanagementwindowdriverupdateprofileaction
schema: 2.0.0
---

# Invoke-MgExecuteDeviceManagementWindowDriverUpdateProfileAction

## SYNOPSIS
Invoke action executeAction

## SYNTAX

### ExecuteExpanded (Default)
```
Invoke-MgExecuteDeviceManagementWindowDriverUpdateProfileAction -WindowsDriverUpdateProfileId <String>
 [-ActionName <String>] [-AdditionalProperties <Hashtable>] [-DeploymentDate <DateTime>]
 [-DriverIds <String[]>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Execute
```
Invoke-MgExecuteDeviceManagementWindowDriverUpdateProfileAction -WindowsDriverUpdateProfileId <String>
 -BodyParameter <IPathsYsc0TiDevicemanagementWindowsdriverupdateprofilesWindowsdriverupdateprofileIdMicrosoftGraphExecuteactionPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ExecuteViaIdentityExpanded
```
Invoke-MgExecuteDeviceManagementWindowDriverUpdateProfileAction -InputObject <IDeviceManagementActionsIdentity>
 [-ActionName <String>] [-AdditionalProperties <Hashtable>] [-DeploymentDate <DateTime>]
 [-DriverIds <String[]>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ExecuteViaIdentity
```
Invoke-MgExecuteDeviceManagementWindowDriverUpdateProfileAction -InputObject <IDeviceManagementActionsIdentity>
 -BodyParameter <IPathsYsc0TiDevicemanagementWindowsdriverupdateprofilesWindowsdriverupdateprofileIdMicrosoftGraphExecuteactionPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action executeAction

## EXAMPLES

## PARAMETERS

### -ActionName
An enum type to represent approval actions of single or list of drivers.

```yaml
Type: String
Parameter Sets: ExecuteExpanded, ExecuteViaIdentityExpanded
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
Parameter Sets: ExecuteExpanded, ExecuteViaIdentityExpanded
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
Type: IPathsYsc0TiDevicemanagementWindowsdriverupdateprofilesWindowsdriverupdateprofileIdMicrosoftGraphExecuteactionPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Execute, ExecuteViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeploymentDate
.

```yaml
Type: DateTime
Parameter Sets: ExecuteExpanded, ExecuteViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DriverIds
.

```yaml
Type: String[]
Parameter Sets: ExecuteExpanded, ExecuteViaIdentityExpanded
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
Type: IDeviceManagementActionsIdentity
Parameter Sets: ExecuteViaIdentityExpanded, ExecuteViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -WindowsDriverUpdateProfileId
key: id of windowsDriverUpdateProfile

```yaml
Type: String
Parameter Sets: ExecuteExpanded, Execute
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementActionsIdentity
### Microsoft.Graph.PowerShell.Models.IPathsYsc0TiDevicemanagementWindowsdriverupdateprofilesWindowsdriverupdateprofileIdMicrosoftGraphExecuteactionPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBulkDriverActionResult
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPathsYsc0TiDevicemanagementWindowsdriverupdateprofilesWindowsdriverupdateprofileIdMicrosoftGraphExecuteactionPostRequestbodyContentApplicationJsonSchema>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ActionName <String>]`: An enum type to represent approval actions of single or list of drivers.
  - `[DeploymentDate <DateTime?>]`: 
  - `[DriverIds <String[]>]`: 

INPUTOBJECT <IDeviceManagementActionsIdentity>: Identity Parameter
  - `[AndroidDeviceOwnerEnrollmentProfileId <String>]`: key: id of androidDeviceOwnerEnrollmentProfile
  - `[AndroidForWorkEnrollmentProfileId <String>]`: key: id of androidForWorkEnrollmentProfile
  - `[AppLogCollectionRequestId <String>]`: key: id of appLogCollectionRequest
  - `[AppleUserInitiatedEnrollmentProfileId <String>]`: key: id of appleUserInitiatedEnrollmentProfile
  - `[CertificateConnectorDetailsId <String>]`: key: id of certificateConnectorDetails
  - `[CloudPcDeviceImageId <String>]`: key: id of cloudPcDeviceImage
  - `[CloudPcId <String>]`: key: id of cloudPC
  - `[CloudPcOnPremisesConnectionId <String>]`: key: id of cloudPcOnPremisesConnection
  - `[CloudPcProvisioningPolicyId <String>]`: key: id of cloudPcProvisioningPolicy
  - `[CloudPcUserSettingId <String>]`: key: id of cloudPcUserSetting
  - `[DataSharingConsentId <String>]`: key: id of dataSharingConsent
  - `[DepOnboardingSettingId <String>]`: key: id of depOnboardingSetting
  - `[DetectedAppId <String>]`: key: id of detectedApp
  - `[DeviceAndAppManagementRoleAssignmentId <String>]`: key: id of deviceAndAppManagementRoleAssignment
  - `[DeviceCompliancePolicyId <String>]`: key: id of deviceCompliancePolicy
  - `[DeviceComplianceScriptId <String>]`: key: id of deviceComplianceScript
  - `[DeviceConfigurationGroupAssignmentId <String>]`: key: id of deviceConfigurationGroupAssignment
  - `[DeviceConfigurationId <String>]`: key: id of deviceConfiguration
  - `[DeviceCustomAttributeShellScriptId <String>]`: key: id of deviceCustomAttributeShellScript
  - `[DeviceEnrollmentConfigurationId <String>]`: key: id of deviceEnrollmentConfiguration
  - `[DeviceHealthScriptDeviceStateId <String>]`: key: id of deviceHealthScriptDeviceState
  - `[DeviceHealthScriptId <String>]`: key: id of deviceHealthScript
  - `[DeviceLogCollectionResponseId <String>]`: key: id of deviceLogCollectionResponse
  - `[DeviceManagementCompliancePolicyId <String>]`: key: id of deviceManagementCompliancePolicy
  - `[DeviceManagementConfigurationPolicyId <String>]`: key: id of deviceManagementConfigurationPolicy
  - `[DeviceManagementExchangeConnectorId <String>]`: key: id of deviceManagementExchangeConnector
  - `[DeviceManagementIntentId <String>]`: key: id of deviceManagementIntent
  - `[DeviceManagementResourceAccessProfileBaseId <String>]`: key: id of deviceManagementResourceAccessProfileBase
  - `[DeviceManagementReusablePolicySettingId <String>]`: key: id of deviceManagementReusablePolicySetting
  - `[DeviceManagementScriptDeviceStateId <String>]`: key: id of deviceManagementScriptDeviceState
  - `[DeviceManagementScriptId <String>]`: key: id of deviceManagementScript
  - `[DeviceManagementTemplateId <String>]`: key: id of deviceManagementTemplate
  - `[DeviceManagementTemplateId1 <String>]`: key: id of deviceManagementTemplate
  - `[DeviceShellScriptId <String>]`: key: id of deviceShellScript
  - `[EmbeddedSimActivationCodePoolId <String>]`: key: id of embeddedSIMActivationCodePool
  - `[EnrollmentProfileId <String>]`: key: id of enrollmentProfile
  - `[GroupPolicyConfigurationId <String>]`: key: id of groupPolicyConfiguration
  - `[GroupPolicyUploadedDefinitionFileId <String>]`: key: id of groupPolicyUploadedDefinitionFile
  - `[IntuneBrandingProfileId <String>]`: key: id of intuneBrandingProfile
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[MicrosoftTunnelServerId <String>]`: key: id of microsoftTunnelServer
  - `[MicrosoftTunnelServerLogCollectionResponseId <String>]`: key: id of microsoftTunnelServerLogCollectionResponse
  - `[MicrosoftTunnelSiteId <String>]`: key: id of microsoftTunnelSite
  - `[MobileAppTroubleshootingEventId <String>]`: key: id of mobileAppTroubleshootingEvent
  - `[NotificationMessageTemplateId <String>]`: key: id of notificationMessageTemplate
  - `[OemWarrantyInformationOnboardingId <String>]`: key: id of oemWarrantyInformationOnboarding
  - `[RemoteAssistancePartnerId <String>]`: key: id of remoteAssistancePartner
  - `[RoleScopeTagId <String>]`: key: id of roleScopeTag
  - `[WindowsAutopilotDeploymentProfileId <String>]`: key: id of windowsAutopilotDeploymentProfile
  - `[WindowsAutopilotDeviceIdentityId <String>]`: key: id of windowsAutopilotDeviceIdentity
  - `[WindowsDriverUpdateProfileId <String>]`: key: id of windowsDriverUpdateProfile
  - `[WindowsFeatureUpdateProfileId <String>]`: key: id of windowsFeatureUpdateProfile
  - `[WindowsQualityUpdateProfileId <String>]`: key: id of windowsQualityUpdateProfile

## RELATED LINKS