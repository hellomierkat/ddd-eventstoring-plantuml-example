# Valve


```text
simpleicons-8/V/Valve
```

```text
include('simpleicons-8/V/Valve')
```



| Illustration | Valve |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/V/Valve.png) | ![illustration for Valve](../../simpleicons-8/V/Valve.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ValveXs>`
- `<$ValveSm>`
- `<$ValveMd>`
- `<$ValveLg>`





## Valve

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Valve
include('simpleicons-8/V/Valve')

' renders the element
Valve('Valve', 'Valve', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Valve
include('simpleicons-8/V/Valve')

' renders the element
Valve('Valve', 'Valve', 'an optional tech label', 'an optional description')
@enduml
```

