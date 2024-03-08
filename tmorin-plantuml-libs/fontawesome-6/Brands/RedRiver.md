# RedRiver


```text
fontawesome-6/Brands/RedRiver
```

```text
include('fontawesome-6/Brands/RedRiver')
```



| Illustration | RedRiver |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/RedRiver.png) | ![illustration for RedRiver](../../fontawesome-6/Brands/RedRiver.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RedRiverXs>`
- `<$RedRiverSm>`
- `<$RedRiverMd>`
- `<$RedRiverLg>`





## RedRiver

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element RedRiver
include('fontawesome-6/Brands/RedRiver')

' renders the element
RedRiver('RedRiver', 'Red River', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element RedRiver
include('fontawesome-6/Brands/RedRiver')

' renders the element
RedRiver('RedRiver', 'Red River', 'an optional tech label', 'an optional description')
@enduml
```

