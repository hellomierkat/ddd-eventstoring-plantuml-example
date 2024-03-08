# Steam


```text
fontawesome-6/Brands/Steam
```

```text
include('fontawesome-6/Brands/Steam')
```



| Illustration | Steam |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Steam.png) | ![illustration for Steam](../../fontawesome-6/Brands/Steam.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SteamXs>`
- `<$SteamSm>`
- `<$SteamMd>`
- `<$SteamLg>`





## Steam

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Steam
include('fontawesome-6/Brands/Steam')

' renders the element
Steam('Steam', 'Steam', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Steam
include('fontawesome-6/Brands/Steam')

' renders the element
Steam('Steam', 'Steam', 'an optional tech label', 'an optional description')
@enduml
```

