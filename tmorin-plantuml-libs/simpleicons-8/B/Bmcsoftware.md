# Bmcsoftware


```text
simpleicons-8/B/Bmcsoftware
```

```text
include('simpleicons-8/B/Bmcsoftware')
```



| Illustration | Bmcsoftware |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Bmcsoftware.png) | ![illustration for Bmcsoftware](../../simpleicons-8/B/Bmcsoftware.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BmcsoftwareXs>`
- `<$BmcsoftwareSm>`
- `<$BmcsoftwareMd>`
- `<$BmcsoftwareLg>`





## Bmcsoftware

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Bmcsoftware
include('simpleicons-8/B/Bmcsoftware')

' renders the element
Bmcsoftware('Bmcsoftware', 'Bmcsoftware', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bmcsoftware
include('simpleicons-8/B/Bmcsoftware')

' renders the element
Bmcsoftware('Bmcsoftware', 'Bmcsoftware', 'an optional tech label', 'an optional description')
@enduml
```

