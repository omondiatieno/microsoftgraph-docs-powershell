---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/invoke-mgfilteridentitygovernanceaccessreviewdefinitioninstancebycurrentuser
schema: 2.0.0
---

# Invoke-MgFilterIdentityGovernanceAccessReviewDefinitionInstanceByCurrentUser

## SYNOPSIS
Invoke function filterByCurrentUser

## SYNTAX

### Filter (Default)
```
Invoke-MgFilterIdentityGovernanceAccessReviewDefinitionInstanceByCurrentUser
 -AccessReviewScheduleDefinitionId <String> -On <String> [<CommonParameters>]
```

### FilterViaIdentity
```
Invoke-MgFilterIdentityGovernanceAccessReviewDefinitionInstanceByCurrentUser
 -InputObject <IIdentityGovernanceIdentity> [<CommonParameters>]
```

## DESCRIPTION
Invoke function filterByCurrentUser

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AccessReviewScheduleDefinitionId
key: id of accessReviewScheduleDefinition

```yaml
Type: String
Parameter Sets: Filter
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
Type: IIdentityGovernanceIdentity
Parameter Sets: FilterViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -On
Usage: on='{on}'

```yaml
Type: String
Parameter Sets: Filter
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IIdentityGovernanceIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAccessReviewInstance
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/invoke-mgfilteridentitygovernanceaccessreviewdefinitioninstancebycurrentuser](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/invoke-mgfilteridentitygovernanceaccessreviewdefinitioninstancebycurrentuser)
