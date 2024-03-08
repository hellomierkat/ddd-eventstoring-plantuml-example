# Steamdeck


```text
simpleicons-8/S/Steamdeck
```

```text
include('simpleicons-8/S/Steamdeck')
```



| Illustration | Steamdeck |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Steamdeck.png) | ![illustration for Steamdeck](../../simpleicons-8/S/Steamdeck.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SteamdeckXs>`
- `<$SteamdeckSm>`
- `<$SteamdeckMd>`
- `<$SteamdeckLg>`





## Steamdeck

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Steamdeck
include('simpleicons-8/S/Steamdeck')

' renders the element
Steamdeck('Steamdeck', 'Steamdeck', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Steamdeck
include('simpleicons-8/S/Steamdeck')

' renders the element
Steamdeck('Steamdeck', 'Steamdeck', 'an optional tech label', 'an optional description')
@enduml
```

