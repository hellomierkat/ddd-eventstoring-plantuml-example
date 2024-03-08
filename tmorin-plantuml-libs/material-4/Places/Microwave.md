# Microwave


```text
material-4/Places/Microwave
```

```text
include('material-4/Places/Microwave')
```



| Illustration | Microwave |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/Microwave.png) | ![illustration for Microwave](../../material-4/Places/Microwave.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MicrowaveXs>`
- `<$MicrowaveSm>`
- `<$MicrowaveMd>`
- `<$MicrowaveLg>`





## Microwave

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Microwave
include('material-4/Places/Microwave')

' renders the element
Microwave('Microwave', 'Microwave', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Microwave
include('material-4/Places/Microwave')

' renders the element
Microwave('Microwave', 'Microwave', 'an optional tech label', 'an optional description')
@enduml
```

