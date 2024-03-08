# MotionPhotosPaused


```text
material-4/Image/MotionPhotosPaused
```

```text
include('material-4/Image/MotionPhotosPaused')
```



| Illustration | MotionPhotosPaused |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/MotionPhotosPaused.png) | ![illustration for MotionPhotosPaused](../../material-4/Image/MotionPhotosPaused.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MotionPhotosPausedXs>`
- `<$MotionPhotosPausedSm>`
- `<$MotionPhotosPausedMd>`
- `<$MotionPhotosPausedLg>`





## MotionPhotosPaused

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element MotionPhotosPaused
include('material-4/Image/MotionPhotosPaused')

' renders the element
MotionPhotosPaused('MotionPhotosPaused', 'Motion Photos Paused', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element MotionPhotosPaused
include('material-4/Image/MotionPhotosPaused')

' renders the element
MotionPhotosPaused('MotionPhotosPaused', 'Motion Photos Paused', 'an optional tech label', 'an optional description')
@enduml
```

