# Bomb


```text
fontawesome-6/Solid/Bomb
```

```text
include('fontawesome-6/Solid/Bomb')
```



| Illustration | Bomb |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Bomb.png) | ![illustration for Bomb](../../fontawesome-6/Solid/Bomb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BombXs>`
- `<$BombSm>`
- `<$BombMd>`
- `<$BombLg>`





## Bomb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Bomb
include('fontawesome-6/Solid/Bomb')

' renders the element
Bomb('Bomb', 'Bomb', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bomb
include('fontawesome-6/Solid/Bomb')

' renders the element
Bomb('Bomb', 'Bomb', 'an optional tech label', 'an optional description')
@enduml
```

