# Outlet


```text
material-4/Action/Outlet
```

```text
include('material-4/Action/Outlet')
```



| Illustration | Outlet |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Outlet.png) | ![illustration for Outlet](../../material-4/Action/Outlet.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OutletXs>`
- `<$OutletSm>`
- `<$OutletMd>`
- `<$OutletLg>`





## Outlet

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Outlet
include('material-4/Action/Outlet')

' renders the element
Outlet('Outlet', 'Outlet', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Outlet
include('material-4/Action/Outlet')

' renders the element
Outlet('Outlet', 'Outlet', 'an optional tech label', 'an optional description')
@enduml
```

