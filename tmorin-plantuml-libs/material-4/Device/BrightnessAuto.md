# BrightnessAuto


```text
material-4/Device/BrightnessAuto
```

```text
include('material-4/Device/BrightnessAuto')
```



| Illustration | BrightnessAuto |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/BrightnessAuto.png) | ![illustration for BrightnessAuto](../../material-4/Device/BrightnessAuto.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BrightnessAutoXs>`
- `<$BrightnessAutoSm>`
- `<$BrightnessAutoMd>`
- `<$BrightnessAutoLg>`





## BrightnessAuto

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BrightnessAuto
include('material-4/Device/BrightnessAuto')

' renders the element
BrightnessAuto('BrightnessAuto', 'Brightness Auto', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BrightnessAuto
include('material-4/Device/BrightnessAuto')

' renders the element
BrightnessAuto('BrightnessAuto', 'Brightness Auto', 'an optional tech label', 'an optional description')
@enduml
```

