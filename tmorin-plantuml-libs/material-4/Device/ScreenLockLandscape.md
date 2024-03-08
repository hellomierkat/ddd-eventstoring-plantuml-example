# ScreenLockLandscape


```text
material-4/Device/ScreenLockLandscape
```

```text
include('material-4/Device/ScreenLockLandscape')
```



| Illustration | ScreenLockLandscape |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/ScreenLockLandscape.png) | ![illustration for ScreenLockLandscape](../../material-4/Device/ScreenLockLandscape.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ScreenLockLandscapeXs>`
- `<$ScreenLockLandscapeSm>`
- `<$ScreenLockLandscapeMd>`
- `<$ScreenLockLandscapeLg>`





## ScreenLockLandscape

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ScreenLockLandscape
include('material-4/Device/ScreenLockLandscape')

' renders the element
ScreenLockLandscape('ScreenLockLandscape', 'Screen Lock Landscape', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ScreenLockLandscape
include('material-4/Device/ScreenLockLandscape')

' renders the element
ScreenLockLandscape('ScreenLockLandscape', 'Screen Lock Landscape', 'an optional tech label', 'an optional description')
@enduml
```

