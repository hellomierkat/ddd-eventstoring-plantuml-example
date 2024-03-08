# SignalCellularAlt


```text
material-4/Device/SignalCellularAlt
```

```text
include('material-4/Device/SignalCellularAlt')
```



| Illustration | SignalCellularAlt |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/SignalCellularAlt.png) | ![illustration for SignalCellularAlt](../../material-4/Device/SignalCellularAlt.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SignalCellularAltXs>`
- `<$SignalCellularAltSm>`
- `<$SignalCellularAltMd>`
- `<$SignalCellularAltLg>`





## SignalCellularAlt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SignalCellularAlt
include('material-4/Device/SignalCellularAlt')

' renders the element
SignalCellularAlt('SignalCellularAlt', 'Signal Cellular Alt', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SignalCellularAlt
include('material-4/Device/SignalCellularAlt')

' renders the element
SignalCellularAlt('SignalCellularAlt', 'Signal Cellular Alt', 'an optional tech label', 'an optional description')
@enduml
```

