# Society6


```text
simpleicons-8/S/Society6
```

```text
include('simpleicons-8/S/Society6')
```



| Illustration | Society6 |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Society6.png) | ![illustration for Society6](../../simpleicons-8/S/Society6.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Society6Xs>`
- `<$Society6Sm>`
- `<$Society6Md>`
- `<$Society6Lg>`





## Society6

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Society6
include('simpleicons-8/S/Society6')

' renders the element
Society6('Society6', 'Society6', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Society6
include('simpleicons-8/S/Society6')

' renders the element
Society6('Society6', 'Society6', 'an optional tech label', 'an optional description')
@enduml
```

