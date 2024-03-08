# TapAndPlay


```text
material-4/Notification/TapAndPlay
```

```text
include('material-4/Notification/TapAndPlay')
```



| Illustration | TapAndPlay |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Notification/TapAndPlay.png) | ![illustration for TapAndPlay](../../material-4/Notification/TapAndPlay.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TapAndPlayXs>`
- `<$TapAndPlaySm>`
- `<$TapAndPlayMd>`
- `<$TapAndPlayLg>`





## TapAndPlay

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element TapAndPlay
include('material-4/Notification/TapAndPlay')

' renders the element
TapAndPlay('TapAndPlay', 'Tap And Play', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TapAndPlay
include('material-4/Notification/TapAndPlay')

' renders the element
TapAndPlay('TapAndPlay', 'Tap And Play', 'an optional tech label', 'an optional description')
@enduml
```

