# Landscape


```text
material-4/Image/Landscape
```

```text
include('material-4/Image/Landscape')
```



| Illustration | Landscape |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Landscape.png) | ![illustration for Landscape](../../material-4/Image/Landscape.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LandscapeXs>`
- `<$LandscapeSm>`
- `<$LandscapeMd>`
- `<$LandscapeLg>`





## Landscape

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Landscape
include('material-4/Image/Landscape')

' renders the element
Landscape('Landscape', 'Landscape', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Landscape
include('material-4/Image/Landscape')

' renders the element
Landscape('Landscape', 'Landscape', 'an optional tech label', 'an optional description')
@enduml
```

