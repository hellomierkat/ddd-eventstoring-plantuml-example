# FlipCameraAndroid


```text
material-4/Image/FlipCameraAndroid
```

```text
include('material-4/Image/FlipCameraAndroid')
```



| Illustration | FlipCameraAndroid |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/FlipCameraAndroid.png) | ![illustration for FlipCameraAndroid](../../material-4/Image/FlipCameraAndroid.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FlipCameraAndroidXs>`
- `<$FlipCameraAndroidSm>`
- `<$FlipCameraAndroidMd>`
- `<$FlipCameraAndroidLg>`





## FlipCameraAndroid

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FlipCameraAndroid
include('material-4/Image/FlipCameraAndroid')

' renders the element
FlipCameraAndroid('FlipCameraAndroid', 'Flip Camera Android', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FlipCameraAndroid
include('material-4/Image/FlipCameraAndroid')

' renders the element
FlipCameraAndroid('FlipCameraAndroid', 'Flip Camera Android', 'an optional tech label', 'an optional description')
@enduml
```

