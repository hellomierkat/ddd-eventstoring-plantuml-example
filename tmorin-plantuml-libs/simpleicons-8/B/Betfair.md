# Betfair


```text
simpleicons-8/B/Betfair
```

```text
include('simpleicons-8/B/Betfair')
```



| Illustration | Betfair |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Betfair.png) | ![illustration for Betfair](../../simpleicons-8/B/Betfair.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BetfairXs>`
- `<$BetfairSm>`
- `<$BetfairMd>`
- `<$BetfairLg>`





## Betfair

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Betfair
include('simpleicons-8/B/Betfair')

' renders the element
Betfair('Betfair', 'Betfair', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Betfair
include('simpleicons-8/B/Betfair')

' renders the element
Betfair('Betfair', 'Betfair', 'an optional tech label', 'an optional description')
@enduml
```

