# WolfPackBattalion


```text
fontawesome-6/Brands/WolfPackBattalion
```

```text
include('fontawesome-6/Brands/WolfPackBattalion')
```



| Illustration | WolfPackBattalion |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/WolfPackBattalion.png) | ![illustration for WolfPackBattalion](../../fontawesome-6/Brands/WolfPackBattalion.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WolfPackBattalionXs>`
- `<$WolfPackBattalionSm>`
- `<$WolfPackBattalionMd>`
- `<$WolfPackBattalionLg>`





## WolfPackBattalion

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element WolfPackBattalion
include('fontawesome-6/Brands/WolfPackBattalion')

' renders the element
WolfPackBattalion('WolfPackBattalion', 'Wolf Pack Battalion', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element WolfPackBattalion
include('fontawesome-6/Brands/WolfPackBattalion')

' renders the element
WolfPackBattalion('WolfPackBattalion', 'Wolf Pack Battalion', 'an optional tech label', 'an optional description')
@enduml
```

