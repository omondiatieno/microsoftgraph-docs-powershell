---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/new-mgidentityconditionalaccesstemplate
schema: 2.0.0
---

# New-MgIdentityConditionalAccessTemplate

## SYNOPSIS
Create new navigation property to templates for identity

## SYNTAX

### CreateExpanded (Default)
```
New-MgIdentityConditionalAccessTemplate [-AdditionalProperties <Hashtable>] [-Description <String>]
 [-Details <IMicrosoftGraphConditionalAccessPolicyDetail>] [-Id <String>] [-Name <String>]
 [-Scenarios <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgIdentityConditionalAccessTemplate -BodyParameter <IMicrosoftGraphConditionalAccessTemplate> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to templates for identity

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
conditionalAccessTemplate
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessTemplate
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Description
The user-friendly name of the template.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Details
conditionalAccessPolicyDetail
To construct, please use Get-Help -Online and see NOTES section for DETAILS properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessPolicyDetail
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique idenfier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The user-friendly name of the template.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Scenarios
templateScenarios

```yaml
Type: String
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphConditionalAccessTemplate
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphConditionalAccessTemplate
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IMicrosoftGraphConditionalAccessTemplate>`: conditionalAccessTemplate
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[Description <String>]`: The user-friendly name of the template.
  - `[Details <IMicrosoftGraphConditionalAccessPolicyDetail>]`: conditionalAccessPolicyDetail
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Conditions <IMicrosoftGraphConditionalAccessConditionSet1>]`: conditionalAccessConditionSet
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Applications <IMicrosoftGraphConditionalAccessApplications1>]`: conditionalAccessApplications
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ApplicationFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Mode <String>]`: filterMode
          - `[Rule <String>]`: Rule syntax is similar to that used for membership rules for groups in Azure Active Directory (Azure AD). For details, see rules with multiple expressions
        - `[ExcludeApplications <String[]>]`: Can be one of the following:  The list of client IDs (appId) explicitly excluded from the policy. Office365 - For the list of apps included in Office365, see Conditional Access target apps: Office 365
        - `[IncludeApplications <String[]>]`: Can be one of the following:  The list of client IDs (appId) the policy applies to, unless explicitly excluded (in excludeApplications)  All  Office365 - For the list of apps included in Office365, see Conditional Access target apps: Office 365
        - `[IncludeAuthenticationContextClassReferences <String[]>]`: Authentication context class references include. Supported values are c1 through c25.
        - `[IncludeUserActions <String[]>]`: User actions to include. Supported values are urn:user:registersecurityinfo and urn:user:registerdevice
      - `[ClientAppTypes <String[]>]`: Client application types included in the policy. Possible values are: all, browser, mobileAppsAndDesktopClients, exchangeActiveSync, easSupported, other. Required.
      - `[ClientApplications <IMicrosoftGraphConditionalAccessClientApplications1>]`: conditionalAccessClientApplications
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExcludeServicePrincipals <String[]>]`: Service principal IDs excluded from the policy scope.
        - `[IncludeServicePrincipals <String[]>]`: Service principal IDs included in the policy scope, or ServicePrincipalsInMyTenant.
        - `[ServicePrincipalFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
      - `[DeviceStates <IMicrosoftGraphConditionalAccessDeviceStates>]`: conditionalAccessDeviceStates
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExcludeStates <String[]>]`: States excluded from the scope of the policy. Possible values: Compliant, DomainJoined.
        - `[IncludeStates <String[]>]`: States in the scope of the policy. All is the only allowed value.
      - `[Devices <IMicrosoftGraphConditionalAccessDevices1>]`: conditionalAccessDevices
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DeviceFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
        - `[ExcludeDeviceStates <String[]>]`: 
        - `[ExcludeDevices <String[]>]`: States excluded from the scope of the policy. Possible values: Compliant, DomainJoined. Cannot be set if deviceFIlter is set.
        - `[IncludeDeviceStates <String[]>]`: 
        - `[IncludeDevices <String[]>]`: States in the scope of the policy. All is the only allowed value. Cannot be set if deviceFIlter is set.
      - `[Locations <IMicrosoftGraphConditionalAccessLocations>]`: conditionalAccessLocations
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExcludeLocations <String[]>]`: Location IDs excluded from scope of policy.
        - `[IncludeLocations <String[]>]`: Location IDs in scope of policy unless explicitly excluded, All, or AllTrusted.
      - `[Platforms <IMicrosoftGraphConditionalAccessPlatforms>]`: conditionalAccessPlatforms
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExcludePlatforms <String[]>]`: Possible values are: android, iOS, windows, windowsPhone, macOS, linux, all, unknownFutureValue.
        - `[IncludePlatforms <String[]>]`: Possible values are: android, iOS, windows, windowsPhone, macOS, linux, all, unknownFutureValue.
      - `[ServicePrincipalRiskLevels <String[]>]`: Service principal risk levels included in the policy. Possible values are: low, medium, high, none, unknownFutureValue.
      - `[SignInRiskLevels <String[]>]`: Sign-in risk levels included in the policy. Possible values are: low, medium, high, hidden, none, unknownFutureValue. Required.
      - `[UserRiskLevels <String[]>]`: User risk levels included in the policy. Possible values are: low, medium, high, hidden, none, unknownFutureValue. Required.
      - `[Users <IMicrosoftGraphConditionalAccessUsers1>]`: conditionalAccessUsers
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExcludeGroups <String[]>]`: Group IDs excluded from scope of policy.
        - `[ExcludeGuestsOrExternalUsers <IMicrosoftGraphConditionalAccessGuestsOrExternalUsers>]`: conditionalAccessGuestsOrExternalUsers
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[ExternalTenants <IMicrosoftGraphConditionalAccessExternalTenants>]`: conditionalAccessExternalTenants
            - `[(Any) <Object>]`: This indicates any property can be added to this object.
            - `[MembershipKind <String>]`: conditionalAccessExternalTenantsMembershipKind
          - `[GuestOrExternalUserTypes <String>]`: conditionalAccessGuestOrExternalUserTypes
        - `[ExcludeRoles <String[]>]`: Role IDs excluded from scope of policy.
        - `[ExcludeUsers <String[]>]`: User IDs excluded from scope of policy and/or GuestsOrExternalUsers.
        - `[IncludeGroups <String[]>]`: Group IDs in scope of policy unless explicitly excluded, or All.
        - `[IncludeGuestsOrExternalUsers <IMicrosoftGraphConditionalAccessGuestsOrExternalUsers>]`: conditionalAccessGuestsOrExternalUsers
        - `[IncludeRoles <String[]>]`: Role IDs in scope of policy unless explicitly excluded, or All.
        - `[IncludeUsers <String[]>]`: User IDs in scope of policy unless explicitly excluded, or None or All or GuestsOrExternalUsers.
    - `[GrantControls <IMicrosoftGraphConditionalAccessGrantControls1>]`: conditionalAccessGrantControls
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AuthenticationStrength <IMicrosoftGraphAuthenticationStrengthPolicy>]`: authenticationStrengthPolicy
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: The unique idenfier for an entity. Read-only.
        - `[AllowedCombinations <String[]>]`: 
        - `[CombinationConfigurations <IMicrosoftGraphAuthenticationCombinationConfiguration[]>]`: 
          - `[Id <String>]`: The unique idenfier for an entity. Read-only.
          - `[AppliesToCombinations <String[]>]`: 
        - `[CreatedDateTime <DateTime?>]`: 
        - `[Description <String>]`: 
        - `[DisplayName <String>]`: 
        - `[ModifiedDateTime <DateTime?>]`: 
        - `[PolicyType <String>]`: authenticationStrengthPolicyType
        - `[RequirementsSatisfied <String>]`: authenticationStrengthRequirements
      - `[BuiltInControls <String[]>]`: List of values of built-in controls required by the policy. Possible values: block, mfa, compliantDevice, domainJoinedDevice, approvedApplication, compliantApplication, passwordChange, unknownFutureValue.
      - `[CustomAuthenticationFactors <String[]>]`: List of custom controls IDs required by the policy. To learn more about custom control, see Custom controls (preview).
      - `[Operator <String>]`: Defines the relationship of the grant controls. Possible values: AND, OR.
      - `[TermsOfUse <String[]>]`: List of terms of use IDs required by the policy.
    - `[SessionControls <IMicrosoftGraphConditionalAccessSessionControls1>]`: conditionalAccessSessionControls
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ApplicationEnforcedRestrictions <IMicrosoftGraphApplicationEnforcedRestrictionsSessionControl>]`: applicationEnforcedRestrictionsSessionControl
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
      - `[CloudAppSecurity <IMicrosoftGraphCloudAppSecuritySessionControl>]`: cloudAppSecuritySessionControl
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
        - `[CloudAppSecurityType <String>]`: cloudAppSecuritySessionControlType
      - `[ContinuousAccessEvaluation <IMicrosoftGraphContinuousAccessEvaluationSessionControl>]`: continuousAccessEvaluationSessionControl
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Mode <String>]`: continuousAccessEvaluationMode
      - `[DisableResilienceDefaults <Boolean?>]`: Session control that determines whether it is acceptable for Azure AD to extend existing sessions based on information collected prior to an outage or not.
      - `[PersistentBrowser <IMicrosoftGraphPersistentBrowserSessionControl>]`: persistentBrowserSessionControl
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
        - `[Mode <String>]`: persistentBrowserSessionMode
      - `[SignInFrequency <IMicrosoftGraphSignInFrequencySessionControl>]`: signInFrequencySessionControl
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
        - `[AuthenticationType <String>]`: signInFrequencyAuthenticationType
        - `[FrequencyInterval <String>]`: signInFrequencyInterval
        - `[Type <String>]`: signinFrequencyType
        - `[Value <Int32?>]`: The number of days or hours.
  - `[Name <String>]`: The user-friendly name of the template.
  - `[Scenarios <String>]`: templateScenarios

DETAILS `<IMicrosoftGraphConditionalAccessPolicyDetail>`: conditionalAccessPolicyDetail
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Conditions <IMicrosoftGraphConditionalAccessConditionSet1>]`: conditionalAccessConditionSet
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Applications <IMicrosoftGraphConditionalAccessApplications1>]`: conditionalAccessApplications
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ApplicationFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Mode <String>]`: filterMode
        - `[Rule <String>]`: Rule syntax is similar to that used for membership rules for groups in Azure Active Directory (Azure AD). For details, see rules with multiple expressions
      - `[ExcludeApplications <String[]>]`: Can be one of the following:  The list of client IDs (appId) explicitly excluded from the policy. Office365 - For the list of apps included in Office365, see Conditional Access target apps: Office 365
      - `[IncludeApplications <String[]>]`: Can be one of the following:  The list of client IDs (appId) the policy applies to, unless explicitly excluded (in excludeApplications)  All  Office365 - For the list of apps included in Office365, see Conditional Access target apps: Office 365
      - `[IncludeAuthenticationContextClassReferences <String[]>]`: Authentication context class references include. Supported values are c1 through c25.
      - `[IncludeUserActions <String[]>]`: User actions to include. Supported values are urn:user:registersecurityinfo and urn:user:registerdevice
    - `[ClientAppTypes <String[]>]`: Client application types included in the policy. Possible values are: all, browser, mobileAppsAndDesktopClients, exchangeActiveSync, easSupported, other. Required.
    - `[ClientApplications <IMicrosoftGraphConditionalAccessClientApplications1>]`: conditionalAccessClientApplications
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ExcludeServicePrincipals <String[]>]`: Service principal IDs excluded from the policy scope.
      - `[IncludeServicePrincipals <String[]>]`: Service principal IDs included in the policy scope, or ServicePrincipalsInMyTenant.
      - `[ServicePrincipalFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
    - `[DeviceStates <IMicrosoftGraphConditionalAccessDeviceStates>]`: conditionalAccessDeviceStates
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ExcludeStates <String[]>]`: States excluded from the scope of the policy. Possible values: Compliant, DomainJoined.
      - `[IncludeStates <String[]>]`: States in the scope of the policy. All is the only allowed value.
    - `[Devices <IMicrosoftGraphConditionalAccessDevices1>]`: conditionalAccessDevices
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DeviceFilter <IMicrosoftGraphConditionalAccessFilter>]`: conditionalAccessFilter
      - `[ExcludeDeviceStates <String[]>]`: 
      - `[ExcludeDevices <String[]>]`: States excluded from the scope of the policy. Possible values: Compliant, DomainJoined. Cannot be set if deviceFIlter is set.
      - `[IncludeDeviceStates <String[]>]`: 
      - `[IncludeDevices <String[]>]`: States in the scope of the policy. All is the only allowed value. Cannot be set if deviceFIlter is set.
    - `[Locations <IMicrosoftGraphConditionalAccessLocations>]`: conditionalAccessLocations
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ExcludeLocations <String[]>]`: Location IDs excluded from scope of policy.
      - `[IncludeLocations <String[]>]`: Location IDs in scope of policy unless explicitly excluded, All, or AllTrusted.
    - `[Platforms <IMicrosoftGraphConditionalAccessPlatforms>]`: conditionalAccessPlatforms
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ExcludePlatforms <String[]>]`: Possible values are: android, iOS, windows, windowsPhone, macOS, linux, all, unknownFutureValue.
      - `[IncludePlatforms <String[]>]`: Possible values are: android, iOS, windows, windowsPhone, macOS, linux, all, unknownFutureValue.
    - `[ServicePrincipalRiskLevels <String[]>]`: Service principal risk levels included in the policy. Possible values are: low, medium, high, none, unknownFutureValue.
    - `[SignInRiskLevels <String[]>]`: Sign-in risk levels included in the policy. Possible values are: low, medium, high, hidden, none, unknownFutureValue. Required.
    - `[UserRiskLevels <String[]>]`: User risk levels included in the policy. Possible values are: low, medium, high, hidden, none, unknownFutureValue. Required.
    - `[Users <IMicrosoftGraphConditionalAccessUsers1>]`: conditionalAccessUsers
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ExcludeGroups <String[]>]`: Group IDs excluded from scope of policy.
      - `[ExcludeGuestsOrExternalUsers <IMicrosoftGraphConditionalAccessGuestsOrExternalUsers>]`: conditionalAccessGuestsOrExternalUsers
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ExternalTenants <IMicrosoftGraphConditionalAccessExternalTenants>]`: conditionalAccessExternalTenants
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[MembershipKind <String>]`: conditionalAccessExternalTenantsMembershipKind
        - `[GuestOrExternalUserTypes <String>]`: conditionalAccessGuestOrExternalUserTypes
      - `[ExcludeRoles <String[]>]`: Role IDs excluded from scope of policy.
      - `[ExcludeUsers <String[]>]`: User IDs excluded from scope of policy and/or GuestsOrExternalUsers.
      - `[IncludeGroups <String[]>]`: Group IDs in scope of policy unless explicitly excluded, or All.
      - `[IncludeGuestsOrExternalUsers <IMicrosoftGraphConditionalAccessGuestsOrExternalUsers>]`: conditionalAccessGuestsOrExternalUsers
      - `[IncludeRoles <String[]>]`: Role IDs in scope of policy unless explicitly excluded, or All.
      - `[IncludeUsers <String[]>]`: User IDs in scope of policy unless explicitly excluded, or None or All or GuestsOrExternalUsers.
  - `[GrantControls <IMicrosoftGraphConditionalAccessGrantControls1>]`: conditionalAccessGrantControls
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AuthenticationStrength <IMicrosoftGraphAuthenticationStrengthPolicy>]`: authenticationStrengthPolicy
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: The unique idenfier for an entity. Read-only.
      - `[AllowedCombinations <String[]>]`: 
      - `[CombinationConfigurations <IMicrosoftGraphAuthenticationCombinationConfiguration[]>]`: 
        - `[Id <String>]`: The unique idenfier for an entity. Read-only.
        - `[AppliesToCombinations <String[]>]`: 
      - `[CreatedDateTime <DateTime?>]`: 
      - `[Description <String>]`: 
      - `[DisplayName <String>]`: 
      - `[ModifiedDateTime <DateTime?>]`: 
      - `[PolicyType <String>]`: authenticationStrengthPolicyType
      - `[RequirementsSatisfied <String>]`: authenticationStrengthRequirements
    - `[BuiltInControls <String[]>]`: List of values of built-in controls required by the policy. Possible values: block, mfa, compliantDevice, domainJoinedDevice, approvedApplication, compliantApplication, passwordChange, unknownFutureValue.
    - `[CustomAuthenticationFactors <String[]>]`: List of custom controls IDs required by the policy. To learn more about custom control, see Custom controls (preview).
    - `[Operator <String>]`: Defines the relationship of the grant controls. Possible values: AND, OR.
    - `[TermsOfUse <String[]>]`: List of terms of use IDs required by the policy.
  - `[SessionControls <IMicrosoftGraphConditionalAccessSessionControls1>]`: conditionalAccessSessionControls
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ApplicationEnforcedRestrictions <IMicrosoftGraphApplicationEnforcedRestrictionsSessionControl>]`: applicationEnforcedRestrictionsSessionControl
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
    - `[CloudAppSecurity <IMicrosoftGraphCloudAppSecuritySessionControl>]`: cloudAppSecuritySessionControl
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
      - `[CloudAppSecurityType <String>]`: cloudAppSecuritySessionControlType
    - `[ContinuousAccessEvaluation <IMicrosoftGraphContinuousAccessEvaluationSessionControl>]`: continuousAccessEvaluationSessionControl
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Mode <String>]`: continuousAccessEvaluationMode
    - `[DisableResilienceDefaults <Boolean?>]`: Session control that determines whether it is acceptable for Azure AD to extend existing sessions based on information collected prior to an outage or not.
    - `[PersistentBrowser <IMicrosoftGraphPersistentBrowserSessionControl>]`: persistentBrowserSessionControl
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
      - `[Mode <String>]`: persistentBrowserSessionMode
    - `[SignInFrequency <IMicrosoftGraphSignInFrequencySessionControl>]`: signInFrequencySessionControl
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsEnabled <Boolean?>]`: Specifies whether the session control is enabled.
      - `[AuthenticationType <String>]`: signInFrequencyAuthenticationType
      - `[FrequencyInterval <String>]`: signInFrequencyInterval
      - `[Type <String>]`: signinFrequencyType
      - `[Value <Int32?>]`: The number of days or hours.

## RELATED LINKS

## RELATED LINKS