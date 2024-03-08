# Platzi


```text
simpleicons-8/P/Platzi
```

```text
include('simpleicons-8/P/Platzi')
```



| Illustration | Platzi |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Platzi.png) | ![illustration for Platzi](../../simpleicons-8/P/Platzi.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PlatziXs>`
- `<$PlatziSm>`
- `<$PlatziMd>`
- `<$PlatziLg>`





## Platzi

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Platzi
include('simpleicons-8/P/Platzi')

' renders the element
Platzi('Platzi', 'Platzi', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Platzi
include('simpleicons-8/P/Platzi')

' renders the element
Platzi('Platzi', 'Platzi', 'an optional tech label', 'an optional description')
@enduml
```

