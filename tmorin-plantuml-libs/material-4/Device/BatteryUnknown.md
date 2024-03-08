# BatteryUnknown


```text
material-4/Device/BatteryUnknown
```

```text
include('material-4/Device/BatteryUnknown')
```



| Illustration | BatteryUnknown |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/BatteryUnknown.png) | ![illustration for BatteryUnknown](../../material-4/Device/BatteryUnknown.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BatteryUnknownXs>`
- `<$BatteryUnknownSm>`
- `<$BatteryUnknownMd>`
- `<$BatteryUnknownLg>`





## BatteryUnknown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BatteryUnknown
include('material-4/Device/BatteryUnknown')

' renders the element
BatteryUnknown('BatteryUnknown', 'Battery Unknown', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BatteryUnknown
include('material-4/Device/BatteryUnknown')

' renders the element
BatteryUnknown('BatteryUnknown', 'Battery Unknown', 'an optional tech label', 'an optional description')
@enduml
```

