# DashboardCustomize


```text
material-4/Action/DashboardCustomize
```

```text
include('material-4/Action/DashboardCustomize')
```



| Illustration | DashboardCustomize |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/DashboardCustomize.png) | ![illustration for DashboardCustomize](../../material-4/Action/DashboardCustomize.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DashboardCustomizeXs>`
- `<$DashboardCustomizeSm>`
- `<$DashboardCustomizeMd>`
- `<$DashboardCustomizeLg>`





## DashboardCustomize

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DashboardCustomize
include('material-4/Action/DashboardCustomize')

' renders the element
DashboardCustomize('DashboardCustomize', 'Dashboard Customize', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DashboardCustomize
include('material-4/Action/DashboardCustomize')

' renders the element
DashboardCustomize('DashboardCustomize', 'Dashboard Customize', 'an optional tech label', 'an optional description')
@enduml
```

