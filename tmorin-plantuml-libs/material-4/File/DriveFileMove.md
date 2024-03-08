# DriveFileMove


```text
material-4/File/DriveFileMove
```

```text
include('material-4/File/DriveFileMove')
```



| Illustration | DriveFileMove |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/File/DriveFileMove.png) | ![illustration for DriveFileMove](../../material-4/File/DriveFileMove.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DriveFileMoveXs>`
- `<$DriveFileMoveSm>`
- `<$DriveFileMoveMd>`
- `<$DriveFileMoveLg>`





## DriveFileMove

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DriveFileMove
include('material-4/File/DriveFileMove')

' renders the element
DriveFileMove('DriveFileMove', 'Drive File Move', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DriveFileMove
include('material-4/File/DriveFileMove')

' renders the element
DriveFileMove('DriveFileMove', 'Drive File Move', 'an optional tech label', 'an optional description')
@enduml
```

