# FolderOpen


```text
fontawesome-6/Solid/FolderOpen
```

```text
include('fontawesome-6/Solid/FolderOpen')
```



| Illustration | FolderOpen |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FolderOpen.png) | ![illustration for FolderOpen](../../fontawesome-6/Solid/FolderOpen.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FolderOpenXs>`
- `<$FolderOpenSm>`
- `<$FolderOpenMd>`
- `<$FolderOpenLg>`





## FolderOpen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FolderOpen
include('fontawesome-6/Solid/FolderOpen')

' renders the element
FolderOpen('FolderOpen', 'Folder Open', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FolderOpen
include('fontawesome-6/Solid/FolderOpen')

' renders the element
FolderOpen('FolderOpen', 'Folder Open', 'an optional tech label', 'an optional description')
@enduml
```

