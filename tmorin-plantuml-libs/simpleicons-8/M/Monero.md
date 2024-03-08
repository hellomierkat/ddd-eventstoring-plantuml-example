# Monero


```text
simpleicons-8/M/Monero
```

```text
include('simpleicons-8/M/Monero')
```



| Illustration | Monero |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Monero.png) | ![illustration for Monero](../../simpleicons-8/M/Monero.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MoneroXs>`
- `<$MoneroSm>`
- `<$MoneroMd>`
- `<$MoneroLg>`





## Monero

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Monero
include('simpleicons-8/M/Monero')

' renders the element
Monero('Monero', 'Monero', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Monero
include('simpleicons-8/M/Monero')

' renders the element
Monero('Monero', 'Monero', 'an optional tech label', 'an optional description')
@enduml
```

