# Commute


```text
material-4/Action/Commute
```

```text
include('material-4/Action/Commute')
```



| Illustration | Commute |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Commute.png) | ![illustration for Commute](../../material-4/Action/Commute.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CommuteXs>`
- `<$CommuteSm>`
- `<$CommuteMd>`
- `<$CommuteLg>`





## Commute

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Commute
include('material-4/Action/Commute')

' renders the element
Commute('Commute', 'Commute', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Commute
include('material-4/Action/Commute')

' renders the element
Commute('Commute', 'Commute', 'an optional tech label', 'an optional description')
@enduml
```

