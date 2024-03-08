# OilWell


```text
fontawesome-6/Solid/OilWell
```

```text
include('fontawesome-6/Solid/OilWell')
```



| Illustration | OilWell |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/OilWell.png) | ![illustration for OilWell](../../fontawesome-6/Solid/OilWell.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OilWellXs>`
- `<$OilWellSm>`
- `<$OilWellMd>`
- `<$OilWellLg>`





## OilWell

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element OilWell
include('fontawesome-6/Solid/OilWell')

' renders the element
OilWell('OilWell', 'Oil Well', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element OilWell
include('fontawesome-6/Solid/OilWell')

' renders the element
OilWell('OilWell', 'Oil Well', 'an optional tech label', 'an optional description')
@enduml
```

