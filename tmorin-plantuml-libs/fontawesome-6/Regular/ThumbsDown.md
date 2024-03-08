# ThumbsDown


```text
fontawesome-6/Regular/ThumbsDown
```

```text
include('fontawesome-6/Regular/ThumbsDown')
```



| Illustration | ThumbsDown |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/ThumbsDown.png) | ![illustration for ThumbsDown](../../fontawesome-6/Regular/ThumbsDown.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ThumbsDownXs>`
- `<$ThumbsDownSm>`
- `<$ThumbsDownMd>`
- `<$ThumbsDownLg>`





## ThumbsDown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ThumbsDown
include('fontawesome-6/Regular/ThumbsDown')

' renders the element
ThumbsDown('ThumbsDown', 'Thumbs Down', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ThumbsDown
include('fontawesome-6/Regular/ThumbsDown')

' renders the element
ThumbsDown('ThumbsDown', 'Thumbs Down', 'an optional tech label', 'an optional description')
@enduml
```

