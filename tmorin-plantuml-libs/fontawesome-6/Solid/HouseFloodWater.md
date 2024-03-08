# HouseFloodWater


```text
fontawesome-6/Solid/HouseFloodWater
```

```text
include('fontawesome-6/Solid/HouseFloodWater')
```



| Illustration | HouseFloodWater |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/HouseFloodWater.png) | ![illustration for HouseFloodWater](../../fontawesome-6/Solid/HouseFloodWater.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HouseFloodWaterXs>`
- `<$HouseFloodWaterSm>`
- `<$HouseFloodWaterMd>`
- `<$HouseFloodWaterLg>`





## HouseFloodWater

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element HouseFloodWater
include('fontawesome-6/Solid/HouseFloodWater')

' renders the element
HouseFloodWater('HouseFloodWater', 'House Flood Water', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HouseFloodWater
include('fontawesome-6/Solid/HouseFloodWater')

' renders the element
HouseFloodWater('HouseFloodWater', 'House Flood Water', 'an optional tech label', 'an optional description')
@enduml
```

