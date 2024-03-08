# PlaylistAdd


```text
material-4/Av/PlaylistAdd
```

```text
include('material-4/Av/PlaylistAdd')
```



| Illustration | PlaylistAdd |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/PlaylistAdd.png) | ![illustration for PlaylistAdd](../../material-4/Av/PlaylistAdd.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PlaylistAddXs>`
- `<$PlaylistAddSm>`
- `<$PlaylistAddMd>`
- `<$PlaylistAddLg>`





## PlaylistAdd

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PlaylistAdd
include('material-4/Av/PlaylistAdd')

' renders the element
PlaylistAdd('PlaylistAdd', 'Playlist Add', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PlaylistAdd
include('material-4/Av/PlaylistAdd')

' renders the element
PlaylistAdd('PlaylistAdd', 'Playlist Add', 'an optional tech label', 'an optional description')
@enduml
```

