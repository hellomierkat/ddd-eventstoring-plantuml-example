# Ghost


```text
simpleicons-8/G/Ghost
```

```text
include('simpleicons-8/G/Ghost')
```



| Illustration | Ghost |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Ghost.png) | ![illustration for Ghost](../../simpleicons-8/G/Ghost.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GhostXs>`
- `<$GhostSm>`
- `<$GhostMd>`
- `<$GhostLg>`





## Ghost

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ghost
include('simpleicons-8/G/Ghost')

' renders the element
Ghost('Ghost', 'Ghost', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ghost
include('simpleicons-8/G/Ghost')

' renders the element
Ghost('Ghost', 'Ghost', 'an optional tech label', 'an optional description')
@enduml
```

