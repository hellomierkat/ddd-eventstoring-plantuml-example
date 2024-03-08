# ThumbDown


```text
material-4/Action/ThumbDown
```

```text
include('material-4/Action/ThumbDown')
```



| Illustration | ThumbDown |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/ThumbDown.png) | ![illustration for ThumbDown](../../material-4/Action/ThumbDown.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ThumbDownXs>`
- `<$ThumbDownSm>`
- `<$ThumbDownMd>`
- `<$ThumbDownLg>`





## ThumbDown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ThumbDown
include('material-4/Action/ThumbDown')

' renders the element
ThumbDown('ThumbDown', 'Thumb Down', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ThumbDown
include('material-4/Action/ThumbDown')

' renders the element
ThumbDown('ThumbDown', 'Thumb Down', 'an optional tech label', 'an optional description')
@enduml
```

