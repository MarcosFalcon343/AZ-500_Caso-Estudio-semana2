# AZ-500_Caso-Estudio-semana2

## Ambientes
### Ambiente sub 1
|Name|Resource group|
|--|--|
|VNET1|RG1|
|VNET2|RG2|
|VNET3|RG3|
|VNET4|RG4|

La sub contiene estás directivas:
|Policy definition| Resource type| Scope|
|--|--|--|
|Allowed resource types| networkSecurityGroups|RG4|
|Not allowed resource types| networkSecurity/subnets|RG5|
|Not allowed resource types| networkSecurityGroups|RG5|
|Not allowed resource types| virtualNetworks/virtualNetworkPeerings|RG6|

La sub contiene estos bloqueos
|Name|Set on| Lock type|
|--|--|--|
|Lock1|RG1|Delete|
|Lock2|RG2|Read-only|
|Lock3|RG3|Delete|
|Lock4|RG3|Read-only|
