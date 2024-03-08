# BluetoothDisabled


```text
material-4/Device/BluetoothDisabled
```

```text
include('material-4/Device/BluetoothDisabled')
```



| Illustration | BluetoothDisabled |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/BluetoothDisabled.png) | ![illustration for BluetoothDisabled](../../material-4/Device/BluetoothDisabled.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BluetoothDisabledXs>`
- `<$BluetoothDisabledSm>`
- `<$BluetoothDisabledMd>`
- `<$BluetoothDisabledLg>`





## BluetoothDisabled

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BluetoothDisabled
include('material-4/Device/BluetoothDisabled')

' renders the element
BluetoothDisabled('BluetoothDisabled', 'Bluetooth Disabled', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BluetoothDisabled
include('material-4/Device/BluetoothDisabled')

' renders the element
BluetoothDisabled('BluetoothDisabled', 'Bluetooth Disabled', 'an optional tech label', 'an optional description')
@enduml
```

