# Video


```text
fontawesome-6/Solid/Video
```

```text
include('fontawesome-6/Solid/Video')
```



| Illustration | Video |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Video.png) | ![illustration for Video](../../fontawesome-6/Solid/Video.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VideoXs>`
- `<$VideoSm>`
- `<$VideoMd>`
- `<$VideoLg>`





## Video

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Video
include('fontawesome-6/Solid/Video')

' renders the element
Video('Video', 'Video', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Video
include('fontawesome-6/Solid/Video')

' renders the element
Video('Video', 'Video', 'an optional tech label', 'an optional description')
@enduml
```

