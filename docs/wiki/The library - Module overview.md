This section provides an overview of the library's feature set.

---

### _Navigation_

- [Feature table](#feature-table)
  - [Legend](#legend)

---

# Feature table

| # | Module | Status | RBAC | Locks | Tags | Diag | PE | PIP | # children | # lines |
| - | - | - | - | - | - | - | - | - | - | - |
| 1 | maintenance<p>maintenance-configuration | [![Maintenance - MaintenanceConfigurations](https://github.com/jdrepo/ResourceModulesJD/workflows/Maintenance%20-%20MaintenanceConfigurations/badge.svg)](https://github.com/jdrepo/ResourceModulesJD/actions/workflows/ms.maintenance.maintenanceconfigurations.yml) | :white_check_mark: | :white_check_mark: | :white_check_mark: |  |  |  |  | 104 |
| Sum | | | 1 | 1 | 1 | 0 | 0 | 0 | 0 | 104 |

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
