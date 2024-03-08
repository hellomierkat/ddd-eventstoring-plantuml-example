# Whitesource


```text
simpleicons-8/W/Whitesource
```

```text
include('simpleicons-8/W/Whitesource')
```



| Illustration | Whitesource |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/W/Whitesource.png) | ![illustration for Whitesource](../../simpleicons-8/W/Whitesource.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WhitesourceXs>`
- `<$WhitesourceSm>`
- `<$WhitesourceMd>`
- `<$WhitesourceLg>`





## Whitesource

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Whitesource
include('simpleicons-8/W/Whitesource')

' renders the element
Whitesource('Whitesource', 'Whitesource', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Whitesource
include('simpleicons-8/W/Whitesource')

' renders the element
Whitesource('Whitesource', 'Whitesource', 'an optional tech label', 'an optional description')
@enduml
```

