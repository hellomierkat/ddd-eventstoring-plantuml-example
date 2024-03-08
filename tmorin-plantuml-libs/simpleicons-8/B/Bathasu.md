# Bathasu


```text
simpleicons-8/B/Bathasu
```

```text
include('simpleicons-8/B/Bathasu')
```



| Illustration | Bathasu |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Bathasu.png) | ![illustration for Bathasu](../../simpleicons-8/B/Bathasu.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BathasuXs>`
- `<$BathasuSm>`
- `<$BathasuMd>`
- `<$BathasuLg>`





## Bathasu

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Bathasu
include('simpleicons-8/B/Bathasu')

' renders the element
Bathasu('Bathasu', 'Bathasu', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bathasu
include('simpleicons-8/B/Bathasu')

' renders the element
Bathasu('Bathasu', 'Bathasu', 'an optional tech label', 'an optional description')
@enduml
```

