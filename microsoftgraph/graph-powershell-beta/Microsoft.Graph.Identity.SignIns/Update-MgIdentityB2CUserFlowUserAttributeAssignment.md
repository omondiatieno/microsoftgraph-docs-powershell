---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityb2cuserflowuserattributeassignment
schema: 2.0.0
---

# Update-MgIdentityB2CUserFlowUserAttributeAssignment

## SYNOPSIS
Update the navigation property userAttributeAssignments in identity

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgIdentityB2CUserFlowUserAttributeAssignment -B2CIdentityUserFlowId <String>
 -IdentityUserFlowAttributeAssignmentId <String> [-AdditionalProperties <Hashtable>] [-DisplayName <String>]
 [-Id <String>] [-IsOptional] [-RequiresVerification]
 [-UserAttribute <IMicrosoftGraphIdentityUserFlowAttribute>]
 [-UserAttributeValues <IMicrosoftGraphUserAttributeValuesItem[]>] [-UserInputType <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgIdentityB2CUserFlowUserAttributeAssignment -B2CIdentityUserFlowId <String>
 -IdentityUserFlowAttributeAssignmentId <String>
 -BodyParameter <IMicrosoftGraphIdentityUserFlowAttributeAssignment> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgIdentityB2CUserFlowUserAttributeAssignment -InputObject <IIdentitySignInsIdentity>
 [-AdditionalProperties <Hashtable>] [-DisplayName <String>] [-Id <String>] [-IsOptional]
 [-RequiresVerification] [-UserAttribute <IMicrosoftGraphIdentityUserFlowAttribute>]
 [-UserAttributeValues <IMicrosoftGraphUserAttributeValuesItem[]>] [-UserInputType <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgIdentityB2CUserFlowUserAttributeAssignment -InputObject <IIdentitySignInsIdentity>
 -BodyParameter <IMicrosoftGraphIdentityUserFlowAttributeAssignment> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property userAttributeAssignments in identity

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

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

### -B2CIdentityUserFlowId
key: id of b2cIdentityUserFlow

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

### -BodyParameter
identityUserFlowAttributeAssignment
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentityUserFlowAttributeAssignment
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DisplayName
The display name of the identityUserFlowAttribute within a user flow.

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

### -IdentityUserFlowAttributeAssignmentId
key: id of identityUserFlowAttributeAssignment

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

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IIdentitySignInsIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsOptional
Determines whether the identityUserFlowAttribute is optional.
true means the user doesn't have to provide a value.
false means the user cannot complete sign-up without providing a value.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: False
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

### -RequiresVerification
Determines whether the identityUserFlowAttribute requires verification.
This is only used for verifying the user's phone number or email address.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserAttribute
identityUserFlowAttribute
To construct, please use Get-Help -Online and see NOTES section for USERATTRIBUTE properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentityUserFlowAttribute
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserAttributeValues
The input options for the user flow attribute.
Only applicable when the userInputType is radioSingleSelect, dropdownSingleSelect, or checkboxMultiSelect.
To construct, please use Get-Help -Online and see NOTES section for USERATTRIBUTEVALUES properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserAttributeValuesItem[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserInputType
identityUserFlowAttributeInputType

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

### Microsoft.Graph.PowerShell.Models.IIdentitySignInsIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIdentityUserFlowAttributeAssignment
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityb2cuserflowuserattributeassignment](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityb2cuserflowuserattributeassignment)
