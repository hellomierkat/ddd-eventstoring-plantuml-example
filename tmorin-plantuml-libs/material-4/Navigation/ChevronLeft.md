# ChevronLeft


```text
material-4/Navigation/ChevronLeft
```

```text
include('material-4/Navigation/ChevronLeft')
```



| Illustration | ChevronLeft |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/ChevronLeft.png) | ![illustration for ChevronLeft](../../material-4/Navigation/ChevronLeft.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ChevronLeftXs>`
- `<$ChevronLeftSm>`
- `<$ChevronLeftMd>`
- `<$ChevronLeftLg>`





## ChevronLeft

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ChevronLeft
include('material-4/Navigation/ChevronLeft')

' renders the element
ChevronLeft('ChevronLeft', 'Chevron Left', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChevronLeft
include('material-4/Navigation/ChevronLeft')

' renders the element
ChevronLeft('ChevronLeft', 'Chevron Left', 'an optional tech label', 'an optional description')
@enduml
```

