# Coins


```text
fontawesome-6/Solid/Coins
```

```text
include('fontawesome-6/Solid/Coins')
```



| Illustration | Coins |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Coins.png) | ![illustration for Coins](../../fontawesome-6/Solid/Coins.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CoinsXs>`
- `<$CoinsSm>`
- `<$CoinsMd>`
- `<$CoinsLg>`





## Coins

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Coins
include('fontawesome-6/Solid/Coins')

' renders the element
Coins('Coins', 'Coins', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Coins
include('fontawesome-6/Solid/Coins')

' renders the element
Coins('Coins', 'Coins', 'an optional tech label', 'an optional description')
@enduml
```

