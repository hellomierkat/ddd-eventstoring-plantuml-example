# SlowMotionVideo


```text
material-4/Av/SlowMotionVideo
```

```text
include('material-4/Av/SlowMotionVideo')
```



| Illustration | SlowMotionVideo |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/SlowMotionVideo.png) | ![illustration for SlowMotionVideo](../../material-4/Av/SlowMotionVideo.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SlowMotionVideoXs>`
- `<$SlowMotionVideoSm>`
- `<$SlowMotionVideoMd>`
- `<$SlowMotionVideoLg>`





## SlowMotionVideo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SlowMotionVideo
include('material-4/Av/SlowMotionVideo')

' renders the element
SlowMotionVideo('SlowMotionVideo', 'Slow Motion Video', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SlowMotionVideo
include('material-4/Av/SlowMotionVideo')

' renders the element
SlowMotionVideo('SlowMotionVideo', 'Slow Motion Video', 'an optional tech label', 'an optional description')
@enduml
```

