# TheaterComedy


```text
material-4/Maps/TheaterComedy
```

```text
include('material-4/Maps/TheaterComedy')
```



| Illustration | TheaterComedy |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/TheaterComedy.png) | ![illustration for TheaterComedy](../../material-4/Maps/TheaterComedy.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TheaterComedyXs>`
- `<$TheaterComedySm>`
- `<$TheaterComedyMd>`
- `<$TheaterComedyLg>`





## TheaterComedy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element TheaterComedy
include('material-4/Maps/TheaterComedy')

' renders the element
TheaterComedy('TheaterComedy', 'Theater Comedy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TheaterComedy
include('material-4/Maps/TheaterComedy')

' renders the element
TheaterComedy('TheaterComedy', 'Theater Comedy', 'an optional tech label', 'an optional description')
@enduml
```

