# Rescuetime


```text
simpleicons-8/R/Rescuetime
```

```text
include('simpleicons-8/R/Rescuetime')
```



| Illustration | Rescuetime |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Rescuetime.png) | ![illustration for Rescuetime](../../simpleicons-8/R/Rescuetime.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RescuetimeXs>`
- `<$RescuetimeSm>`
- `<$RescuetimeMd>`
- `<$RescuetimeLg>`





## Rescuetime

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Rescuetime
include('simpleicons-8/R/Rescuetime')

' renders the element
Rescuetime('Rescuetime', 'Rescuetime', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rescuetime
include('simpleicons-8/R/Rescuetime')

' renders the element
Rescuetime('Rescuetime', 'Rescuetime', 'an optional tech label', 'an optional description')
@enduml
```

