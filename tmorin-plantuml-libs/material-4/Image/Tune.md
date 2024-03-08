# Tune


```text
material-4/Image/Tune
```

```text
include('material-4/Image/Tune')
```



| Illustration | Tune |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Tune.png) | ![illustration for Tune](../../material-4/Image/Tune.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TuneXs>`
- `<$TuneSm>`
- `<$TuneMd>`
- `<$TuneLg>`





## Tune

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Tune
include('material-4/Image/Tune')

' renders the element
Tune('Tune', 'Tune', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Tune
include('material-4/Image/Tune')

' renders the element
Tune('Tune', 'Tune', 'an optional tech label', 'an optional description')
@enduml
```

