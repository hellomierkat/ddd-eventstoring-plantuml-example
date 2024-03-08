# Ifixit


```text
simpleicons-8/I/Ifixit
```

```text
include('simpleicons-8/I/Ifixit')
```



| Illustration | Ifixit |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Ifixit.png) | ![illustration for Ifixit](../../simpleicons-8/I/Ifixit.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IfixitXs>`
- `<$IfixitSm>`
- `<$IfixitMd>`
- `<$IfixitLg>`





## Ifixit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ifixit
include('simpleicons-8/I/Ifixit')

' renders the element
Ifixit('Ifixit', 'Ifixit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ifixit
include('simpleicons-8/I/Ifixit')

' renders the element
Ifixit('Ifixit', 'Ifixit', 'an optional tech label', 'an optional description')
@enduml
```

