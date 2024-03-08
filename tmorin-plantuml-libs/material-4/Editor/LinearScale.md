# LinearScale


```text
material-4/Editor/LinearScale
```

```text
include('material-4/Editor/LinearScale')
```



| Illustration | LinearScale |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/LinearScale.png) | ![illustration for LinearScale](../../material-4/Editor/LinearScale.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LinearScaleXs>`
- `<$LinearScaleSm>`
- `<$LinearScaleMd>`
- `<$LinearScaleLg>`





## LinearScale

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LinearScale
include('material-4/Editor/LinearScale')

' renders the element
LinearScale('LinearScale', 'Linear Scale', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LinearScale
include('material-4/Editor/LinearScale')

' renders the element
LinearScale('LinearScale', 'Linear Scale', 'an optional tech label', 'an optional description')
@enduml
```

