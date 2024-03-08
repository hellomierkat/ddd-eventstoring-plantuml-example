# Monero


```text
fontawesome-6/Brands/Monero
```

```text
include('fontawesome-6/Brands/Monero')
```



| Illustration | Monero |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Monero.png) | ![illustration for Monero](../../fontawesome-6/Brands/Monero.Local.png) |



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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Monero
include('fontawesome-6/Brands/Monero')

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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Monero
include('fontawesome-6/Brands/Monero')

' renders the element
Monero('Monero', 'Monero', 'an optional tech label', 'an optional description')
@enduml
```

