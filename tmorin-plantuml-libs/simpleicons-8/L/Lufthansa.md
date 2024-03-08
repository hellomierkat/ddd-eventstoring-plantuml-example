# Lufthansa


```text
simpleicons-8/L/Lufthansa
```

```text
include('simpleicons-8/L/Lufthansa')
```



| Illustration | Lufthansa |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Lufthansa.png) | ![illustration for Lufthansa](../../simpleicons-8/L/Lufthansa.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LufthansaXs>`
- `<$LufthansaSm>`
- `<$LufthansaMd>`
- `<$LufthansaLg>`





## Lufthansa

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Lufthansa
include('simpleicons-8/L/Lufthansa')

' renders the element
Lufthansa('Lufthansa', 'Lufthansa', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Lufthansa
include('simpleicons-8/L/Lufthansa')

' renders the element
Lufthansa('Lufthansa', 'Lufthansa', 'an optional tech label', 'an optional description')
@enduml
```

