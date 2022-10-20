---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/new-mgidentitygovernancelifecycleworkflowtaskdefinition
schema: 2.0.0
---

# New-MgIdentityGovernanceLifecycleWorkflowTaskDefinition

## SYNOPSIS
Create new navigation property to taskDefinitions for identityGovernance

## SYNTAX

### CreateExpanded (Default)
```
New-MgIdentityGovernanceLifecycleWorkflowTaskDefinition [-AdditionalProperties <Hashtable>]
 [-Category <String>] [-ContinueOnError] [-Description <String>] [-DisplayName <String>] [-Id <String>]
 [-Parameters <IMicrosoftGraphIdentityGovernanceParameter[]>] [-Version <Int32>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Create
```
New-MgIdentityGovernanceLifecycleWorkflowTaskDefinition
 -BodyParameter <IMicrosoftGraphIdentityGovernanceTaskDefinition> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to taskDefinitions for identityGovernance

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
taskDefinition
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentityGovernanceTaskDefinition
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Category
lifecycleTaskCategory

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

### -ContinueOnError
.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The description of the taskDefinition.

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

### -DisplayName
The display name of the taskDefinition`.

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

### -Parameters
The parameters that must be supplied when creating a workflow task object.
To construct, please use Get-Help -Online and see NOTES section for PARAMETERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentityGovernanceParameter[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
The version number of the taskDefinition.
New records are pushed when we add support for new parameters.

```yaml
Type: Int32
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIdentityGovernanceTaskDefinition
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIdentityGovernanceTaskDefinition
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IMicrosoftGraphIdentityGovernanceTaskDefinition>`: taskDefinition
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[Category <String>]`: lifecycleTaskCategory
  - `[ContinueOnError <Boolean?>]`: 
  - `[Description <String>]`: The description of the taskDefinition.
  - `[DisplayName <String>]`: The display name of the taskDefinition`.
  - `[Parameters <IMicrosoftGraphIdentityGovernanceParameter[]>]`: The parameters that must be supplied when creating a workflow task object.
    - `[Name <String>]`: The name of the parameter.
    - `[ValueType <String>]`: valueType
    - `[Values <String[]>]`: The values of the parameter.
  - `[Version <Int32?>]`: The version number of the taskDefinition. New records are pushed when we add support for new parameters.

PARAMETERS <IMicrosoftGraphIdentityGovernanceParameter\[]>: The parameters that must be supplied when creating a workflow task object.
  - `[Name <String>]`: The name of the parameter.
  - `[ValueType <String>]`: valueType
  - `[Values <String[]>]`: The values of the parameter.

## RELATED LINKS