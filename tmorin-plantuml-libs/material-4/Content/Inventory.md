# Inventory


```text
material-4/Content/Inventory
```

```text
include('material-4/Content/Inventory')
```



| Illustration | Inventory |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Inventory.png) | ![illustration for Inventory](../../material-4/Content/Inventory.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$InventoryXs>`
- `<$InventorySm>`
- `<$InventoryMd>`
- `<$InventoryLg>`





## Inventory

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Inventory
include('material-4/Content/Inventory')

' renders the element
Inventory('Inventory', 'Inventory', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Inventory
include('material-4/Content/Inventory')

' renders the element
Inventory('Inventory', 'Inventory', 'an optional tech label', 'an optional description')
@enduml
```

