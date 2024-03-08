# BatteryFull


```text
fontawesome-6/Solid/BatteryFull
```

```text
include('fontawesome-6/Solid/BatteryFull')
```



| Illustration | BatteryFull |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BatteryFull.png) | ![illustration for BatteryFull](../../fontawesome-6/Solid/BatteryFull.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BatteryFullXs>`
- `<$BatteryFullSm>`
- `<$BatteryFullMd>`
- `<$BatteryFullLg>`





## BatteryFull

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BatteryFull
include('fontawesome-6/Solid/BatteryFull')

' renders the element
BatteryFull('BatteryFull', 'Battery Full', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BatteryFull
include('fontawesome-6/Solid/BatteryFull')

' renders the element
BatteryFull('BatteryFull', 'Battery Full', 'an optional tech label', 'an optional description')
@enduml
```

