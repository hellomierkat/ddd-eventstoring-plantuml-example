# BridgeWater


```text
fontawesome-6/Solid/BridgeWater
```

```text
include('fontawesome-6/Solid/BridgeWater')
```



| Illustration | BridgeWater |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BridgeWater.png) | ![illustration for BridgeWater](../../fontawesome-6/Solid/BridgeWater.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BridgeWaterXs>`
- `<$BridgeWaterSm>`
- `<$BridgeWaterMd>`
- `<$BridgeWaterLg>`





## BridgeWater

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BridgeWater
include('fontawesome-6/Solid/BridgeWater')

' renders the element
BridgeWater('BridgeWater', 'Bridge Water', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BridgeWater
include('fontawesome-6/Solid/BridgeWater')

' renders the element
BridgeWater('BridgeWater', 'Bridge Water', 'an optional tech label', 'an optional description')
@enduml
```

