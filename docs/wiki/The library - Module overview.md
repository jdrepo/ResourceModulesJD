This section provides an overview of the library's feature set.

---

### _Navigation_

- [Feature table](#feature-table)
  - [Legend](#legend)

---

# Feature table

| # | Module | Status | RBAC | Locks | Tags | Diag | PE | PIP | # children | # lines |
| - | - | - | - | - | - | - | - | - | - | - |
| 1 | authorization<p>lock | [![Authorization - Locks](https://github.com/jdrepo/ResourceModulesJD/workflows/Authorization%20-%20Locks/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.authorization.locks.yml) |  |  |  |  |  |  | [L1:2] | 62 |
| 2 | maintenance<p>maintenance-configuration | [![Maintenance - MaintenanceConfigurations](https://github.com/jdrepo/ResourceModulesJD/workflows/Maintenance%20-%20MaintenanceConfigurations/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.maintenance.maintenanceconfigurations.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: |  |  |  |  | 108 |
| 3 | network<p>private-endpoint | [![Network - PrivateEndpoints](https://github.com/jdrepo/ResourceModulesJD/workflows/Network%20-%20PrivateEndpoints/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.network.privateendpoints.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: |  |  |  | [L1:1] | 111 |
| 4 | network<p>virtual-network | [![Network - VirtualNetworks](https://github.com/jdrepo/ResourceModulesJD/workflows/Network%20-%20VirtualNetworks/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.network.virtualnetworks.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |  |  | [L1:2] | 247 |
| 5 | resources<p>deployment-script | [![Resources - DeploymentScripts](https://github.com/jdrepo/ResourceModulesJD/workflows/Resources%20-%20DeploymentScripts/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.resources.deploymentscripts.yml) |  | :white_check_mark: | :white_check_mark: |  |  |  |  | 124 |
| 6 | resources<p>resource-group | [![Resources - ResourceGroups](https://github.com/jdrepo/ResourceModulesJD/workflows/Resources%20-%20ResourceGroups/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.resources.resourcegroups.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: |  |  |  |  | 69 |
| 7 | storage<p>storage-account | [![Storage - StorageAccounts](https://github.com/jdrepo/ResourceModulesJD/workflows/Storage%20-%20StorageAccounts/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.storage.storageaccounts.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |  | [L1:6, L2:4, L3:1] | 425 |
| Sum | | | 5 | 6 | 6 | 2 | 1 | 0 | 16 | 1146 |

## Legend

| Term | Description |
| - | - |
| `Module` | The name of the module. |
| `RBAC` | Whether the module can deploy _Role Assignments_. |
| `Locks` | Whether the module can deploy _Locks_. |
| `Tags` | Whether the module can deploy _Tags_. |
| `Diag` | Whether the module can deploy _Diagnostic Settings_. |
| `PE` | Whether the module can deploy _Private Endpoints_. |
| `PIP` | Whether the module can deploy a _Public IP_ as a secondary resource. |
| `# children` | The number of children in the given module. Children (if any) are displayed in format `[L1:5, L2:4, L3:1]`. Each item (separated via ',') shows the level of nesting in the front (e.g. L1) and the number of children in this level (separated by a colon ':'). In the previous example, the module has 5 direct children, 4 of them have direct children themselves and 1 of them has 1 more child. |
| `# lines` | The number of lines in the module Bicep deployment file. |
