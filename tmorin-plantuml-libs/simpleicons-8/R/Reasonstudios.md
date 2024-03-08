# Reasonstudios


```text
simpleicons-8/R/Reasonstudios
```

```text
include('simpleicons-8/R/Reasonstudios')
```



| Illustration | Reasonstudios |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Reasonstudios.png) | ![illustration for Reasonstudios](../../simpleicons-8/R/Reasonstudios.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReasonstudiosXs>`
- `<$ReasonstudiosSm>`
- `<$ReasonstudiosMd>`
- `<$ReasonstudiosLg>`





## Reasonstudios

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Reasonstudios
include('simpleicons-8/R/Reasonstudios')

' renders the element
Reasonstudios('Reasonstudios', 'Reasonstudios', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Reasonstudios
include('simpleicons-8/R/Reasonstudios')

' renders the element
Reasonstudios('Reasonstudios', 'Reasonstudios', 'an optional tech label', 'an optional description')
@enduml
```

