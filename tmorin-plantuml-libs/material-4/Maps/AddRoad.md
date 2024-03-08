# AddRoad


```text
material-4/Maps/AddRoad
```

```text
include('material-4/Maps/AddRoad')
```



| Illustration | AddRoad |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/AddRoad.png) | ![illustration for AddRoad](../../material-4/Maps/AddRoad.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddRoadXs>`
- `<$AddRoadSm>`
- `<$AddRoadMd>`
- `<$AddRoadLg>`





## AddRoad

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AddRoad
include('material-4/Maps/AddRoad')

' renders the element
AddRoad('AddRoad', 'Add Road', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AddRoad
include('material-4/Maps/AddRoad')

' renders the element
AddRoad('AddRoad', 'Add Road', 'an optional tech label', 'an optional description')
@enduml
```

