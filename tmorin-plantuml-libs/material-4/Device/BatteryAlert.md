# BatteryAlert


```text
material-4/Device/BatteryAlert
```

```text
include('material-4/Device/BatteryAlert')
```



| Illustration | BatteryAlert |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/BatteryAlert.png) | ![illustration for BatteryAlert](../../material-4/Device/BatteryAlert.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BatteryAlertXs>`
- `<$BatteryAlertSm>`
- `<$BatteryAlertMd>`
- `<$BatteryAlertLg>`





## BatteryAlert

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BatteryAlert
include('material-4/Device/BatteryAlert')

' renders the element
BatteryAlert('BatteryAlert', 'Battery Alert', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BatteryAlert
include('material-4/Device/BatteryAlert')

' renders the element
BatteryAlert('BatteryAlert', 'Battery Alert', 'an optional tech label', 'an optional description')
@enduml
```

