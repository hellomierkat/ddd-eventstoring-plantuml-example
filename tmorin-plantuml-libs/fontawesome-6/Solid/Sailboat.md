# Sailboat


```text
fontawesome-6/Solid/Sailboat
```

```text
include('fontawesome-6/Solid/Sailboat')
```



| Illustration | Sailboat |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Sailboat.png) | ![illustration for Sailboat](../../fontawesome-6/Solid/Sailboat.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SailboatXs>`
- `<$SailboatSm>`
- `<$SailboatMd>`
- `<$SailboatLg>`





## Sailboat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Sailboat
include('fontawesome-6/Solid/Sailboat')

' renders the element
Sailboat('Sailboat', 'Sailboat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sailboat
include('fontawesome-6/Solid/Sailboat')

' renders the element
Sailboat('Sailboat', 'Sailboat', 'an optional tech label', 'an optional description')
@enduml
```

