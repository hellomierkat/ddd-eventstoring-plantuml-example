# Dedge


```text
simpleicons-8/D/Dedge
```

```text
include('simpleicons-8/D/Dedge')
```



| Illustration | Dedge |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/D/Dedge.png) | ![illustration for Dedge](../../simpleicons-8/D/Dedge.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DedgeXs>`
- `<$DedgeSm>`
- `<$DedgeMd>`
- `<$DedgeLg>`





## Dedge

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Dedge
include('simpleicons-8/D/Dedge')

' renders the element
Dedge('Dedge', 'Dedge', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Dedge
include('simpleicons-8/D/Dedge')

' renders the element
Dedge('Dedge', 'Dedge', 'an optional tech label', 'an optional description')
@enduml
```

