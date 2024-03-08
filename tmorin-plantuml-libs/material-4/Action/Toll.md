# Toll


```text
material-4/Action/Toll
```

```text
include('material-4/Action/Toll')
```



| Illustration | Toll |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Toll.png) | ![illustration for Toll](../../material-4/Action/Toll.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TollXs>`
- `<$TollSm>`
- `<$TollMd>`
- `<$TollLg>`





## Toll

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Toll
include('material-4/Action/Toll')

' renders the element
Toll('Toll', 'Toll', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Toll
include('material-4/Action/Toll')

' renders the element
Toll('Toll', 'Toll', 'an optional tech label', 'an optional description')
@enduml
```

