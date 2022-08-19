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
|Allowed resource types| networkSecurityGroups|RG4|
|Not allowed resource types| networkSecurity/subnets|RG5|
|Not allowed resource types| virtualNetworks/virtualNetworkPeerings|RG6|
