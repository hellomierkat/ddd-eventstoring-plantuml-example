# Polywork


```text
simpleicons-8/P/Polywork
```

```text
include('simpleicons-8/P/Polywork')
```



| Illustration | Polywork |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Polywork.png) | ![illustration for Polywork](../../simpleicons-8/P/Polywork.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PolyworkXs>`
- `<$PolyworkSm>`
- `<$PolyworkMd>`
- `<$PolyworkLg>`





## Polywork

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Polywork
include('simpleicons-8/P/Polywork')

' renders the element
Polywork('Polywork', 'Polywork', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Polywork
include('simpleicons-8/P/Polywork')

' renders the element
Polywork('Polywork', 'Polywork', 'an optional tech label', 'an optional description')
@enduml
```

