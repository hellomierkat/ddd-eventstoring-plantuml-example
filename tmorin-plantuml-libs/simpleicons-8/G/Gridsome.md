# Gridsome


```text
simpleicons-8/G/Gridsome
```

```text
include('simpleicons-8/G/Gridsome')
```



| Illustration | Gridsome |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gridsome.png) | ![illustration for Gridsome](../../simpleicons-8/G/Gridsome.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GridsomeXs>`
- `<$GridsomeSm>`
- `<$GridsomeMd>`
- `<$GridsomeLg>`





## Gridsome

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gridsome
include('simpleicons-8/G/Gridsome')

' renders the element
Gridsome('Gridsome', 'Gridsome', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gridsome
include('simpleicons-8/G/Gridsome')

' renders the element
Gridsome('Gridsome', 'Gridsome', 'an optional tech label', 'an optional description')
@enduml
```

