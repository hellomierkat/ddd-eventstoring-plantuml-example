# AddToHomeScreen


```text
material-4/Device/AddToHomeScreen
```

```text
include('material-4/Device/AddToHomeScreen')
```



| Illustration | AddToHomeScreen |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/AddToHomeScreen.png) | ![illustration for AddToHomeScreen](../../material-4/Device/AddToHomeScreen.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddToHomeScreenXs>`
- `<$AddToHomeScreenSm>`
- `<$AddToHomeScreenMd>`
- `<$AddToHomeScreenLg>`





## AddToHomeScreen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AddToHomeScreen
include('material-4/Device/AddToHomeScreen')

' renders the element
AddToHomeScreen('AddToHomeScreen', 'Add To Home Screen', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AddToHomeScreen
include('material-4/Device/AddToHomeScreen')

' renders the element
AddToHomeScreen('AddToHomeScreen', 'Add To Home Screen', 'an optional tech label', 'an optional description')
@enduml
```

