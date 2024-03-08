# ChargingStation


```text
fontawesome-6/Solid/ChargingStation
```

```text
include('fontawesome-6/Solid/ChargingStation')
```



| Illustration | ChargingStation |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ChargingStation.png) | ![illustration for ChargingStation](../../fontawesome-6/Solid/ChargingStation.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ChargingStationXs>`
- `<$ChargingStationSm>`
- `<$ChargingStationMd>`
- `<$ChargingStationLg>`





## ChargingStation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ChargingStation
include('fontawesome-6/Solid/ChargingStation')

' renders the element
ChargingStation('ChargingStation', 'Charging Station', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChargingStation
include('fontawesome-6/Solid/ChargingStation')

' renders the element
ChargingStation('ChargingStation', 'Charging Station', 'an optional tech label', 'an optional description')
@enduml
```

