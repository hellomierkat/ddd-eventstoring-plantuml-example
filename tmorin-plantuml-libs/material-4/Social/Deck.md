# Deck


```text
material-4/Social/Deck
```

```text
include('material-4/Social/Deck')
```



| Illustration | Deck |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/Deck.png) | ![illustration for Deck](../../material-4/Social/Deck.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DeckXs>`
- `<$DeckSm>`
- `<$DeckMd>`
- `<$DeckLg>`





## Deck

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Deck
include('material-4/Social/Deck')

' renders the element
Deck('Deck', 'Deck', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Deck
include('material-4/Social/Deck')

' renders the element
Deck('Deck', 'Deck', 'an optional tech label', 'an optional description')
@enduml
```

