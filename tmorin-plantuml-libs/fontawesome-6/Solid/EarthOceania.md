# EarthOceania


```text
fontawesome-6/Solid/EarthOceania
```

```text
include('fontawesome-6/Solid/EarthOceania')
```



| Illustration | EarthOceania |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/EarthOceania.png) | ![illustration for EarthOceania](../../fontawesome-6/Solid/EarthOceania.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EarthOceaniaXs>`
- `<$EarthOceaniaSm>`
- `<$EarthOceaniaMd>`
- `<$EarthOceaniaLg>`





## EarthOceania

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element EarthOceania
include('fontawesome-6/Solid/EarthOceania')

' renders the element
EarthOceania('EarthOceania', 'Earth Oceania', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element EarthOceania
include('fontawesome-6/Solid/EarthOceania')

' renders the element
EarthOceania('EarthOceania', 'Earth Oceania', 'an optional tech label', 'an optional description')
@enduml
```

