# Ryanair


```text
simpleicons-8/R/Ryanair
```

```text
include('simpleicons-8/R/Ryanair')
```



| Illustration | Ryanair |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Ryanair.png) | ![illustration for Ryanair](../../simpleicons-8/R/Ryanair.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RyanairXs>`
- `<$RyanairSm>`
- `<$RyanairMd>`
- `<$RyanairLg>`





## Ryanair

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ryanair
include('simpleicons-8/R/Ryanair')

' renders the element
Ryanair('Ryanair', 'Ryanair', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ryanair
include('simpleicons-8/R/Ryanair')

' renders the element
Ryanair('Ryanair', 'Ryanair', 'an optional tech label', 'an optional description')
@enduml
```

