# FullscreenExit


```text
material-4/Navigation/FullscreenExit
```

```text
include('material-4/Navigation/FullscreenExit')
```



| Illustration | FullscreenExit |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/FullscreenExit.png) | ![illustration for FullscreenExit](../../material-4/Navigation/FullscreenExit.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FullscreenExitXs>`
- `<$FullscreenExitSm>`
- `<$FullscreenExitMd>`
- `<$FullscreenExitLg>`





## FullscreenExit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FullscreenExit
include('material-4/Navigation/FullscreenExit')

' renders the element
FullscreenExit('FullscreenExit', 'Fullscreen Exit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FullscreenExit
include('material-4/Navigation/FullscreenExit')

' renders the element
FullscreenExit('FullscreenExit', 'Fullscreen Exit', 'an optional tech label', 'an optional description')
@enduml
```

