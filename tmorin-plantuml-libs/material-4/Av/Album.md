# Album


```text
material-4/Av/Album
```

```text
include('material-4/Av/Album')
```



| Illustration | Album |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/Album.png) | ![illustration for Album](../../material-4/Av/Album.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AlbumXs>`
- `<$AlbumSm>`
- `<$AlbumMd>`
- `<$AlbumLg>`





## Album

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Album
include('material-4/Av/Album')

' renders the element
Album('Album', 'Album', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Album
include('material-4/Av/Album')

' renders the element
Album('Album', 'Album', 'an optional tech label', 'an optional description')
@enduml
```

