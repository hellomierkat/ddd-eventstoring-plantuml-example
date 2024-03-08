# TowerObservation


```text
fontawesome-6/Solid/TowerObservation
```

```text
include('fontawesome-6/Solid/TowerObservation')
```



| Illustration | TowerObservation |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/TowerObservation.png) | ![illustration for TowerObservation](../../fontawesome-6/Solid/TowerObservation.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TowerObservationXs>`
- `<$TowerObservationSm>`
- `<$TowerObservationMd>`
- `<$TowerObservationLg>`





## TowerObservation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TowerObservation
include('fontawesome-6/Solid/TowerObservation')

' renders the element
TowerObservation('TowerObservation', 'Tower Observation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TowerObservation
include('fontawesome-6/Solid/TowerObservation')

' renders the element
TowerObservation('TowerObservation', 'Tower Observation', 'an optional tech label', 'an optional description')
@enduml
```

