# Underarmour


```text
simpleicons-8/U/Underarmour
```

```text
include('simpleicons-8/U/Underarmour')
```



| Illustration | Underarmour |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/U/Underarmour.png) | ![illustration for Underarmour](../../simpleicons-8/U/Underarmour.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$UnderarmourXs>`
- `<$UnderarmourSm>`
- `<$UnderarmourMd>`
- `<$UnderarmourLg>`





## Underarmour

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Underarmour
include('simpleicons-8/U/Underarmour')

' renders the element
Underarmour('Underarmour', 'Underarmour', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Underarmour
include('simpleicons-8/U/Underarmour')

' renders the element
Underarmour('Underarmour', 'Underarmour', 'an optional tech label', 'an optional description')
@enduml
```

