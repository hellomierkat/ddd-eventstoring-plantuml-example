# Reactrouter


```text
simpleicons-8/R/Reactrouter
```

```text
include('simpleicons-8/R/Reactrouter')
```



| Illustration | Reactrouter |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Reactrouter.png) | ![illustration for Reactrouter](../../simpleicons-8/R/Reactrouter.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReactrouterXs>`
- `<$ReactrouterSm>`
- `<$ReactrouterMd>`
- `<$ReactrouterLg>`





## Reactrouter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Reactrouter
include('simpleicons-8/R/Reactrouter')

' renders the element
Reactrouter('Reactrouter', 'Reactrouter', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reactrouter
include('simpleicons-8/R/Reactrouter')

' renders the element
Reactrouter('Reactrouter', 'Reactrouter', 'an optional tech label', 'an optional description')
@enduml
```

