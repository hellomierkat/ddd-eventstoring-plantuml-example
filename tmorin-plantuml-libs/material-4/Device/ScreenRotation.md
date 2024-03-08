# ScreenRotation


```text
material-4/Device/ScreenRotation
```

```text
include('material-4/Device/ScreenRotation')
```



| Illustration | ScreenRotation |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/ScreenRotation.png) | ![illustration for ScreenRotation](../../material-4/Device/ScreenRotation.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ScreenRotationXs>`
- `<$ScreenRotationSm>`
- `<$ScreenRotationMd>`
- `<$ScreenRotationLg>`





## ScreenRotation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ScreenRotation
include('material-4/Device/ScreenRotation')

' renders the element
ScreenRotation('ScreenRotation', 'Screen Rotation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ScreenRotation
include('material-4/Device/ScreenRotation')

' renders the element
ScreenRotation('ScreenRotation', 'Screen Rotation', 'an optional tech label', 'an optional description')
@enduml
```

