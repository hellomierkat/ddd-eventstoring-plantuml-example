# Airchina


```text
simpleicons-8/A/Airchina
```

```text
include('simpleicons-8/A/Airchina')
```



| Illustration | Airchina |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Airchina.png) | ![illustration for Airchina](../../simpleicons-8/A/Airchina.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AirchinaXs>`
- `<$AirchinaSm>`
- `<$AirchinaMd>`
- `<$AirchinaLg>`





## Airchina

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Airchina
include('simpleicons-8/A/Airchina')

' renders the element
Airchina('Airchina', 'Airchina', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Airchina
include('simpleicons-8/A/Airchina')

' renders the element
Airchina('Airchina', 'Airchina', 'an optional tech label', 'an optional description')
@enduml
```

