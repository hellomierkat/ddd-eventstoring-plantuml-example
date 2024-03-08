# Plotly


```text
simpleicons-8/P/Plotly
```

```text
include('simpleicons-8/P/Plotly')
```



| Illustration | Plotly |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Plotly.png) | ![illustration for Plotly](../../simpleicons-8/P/Plotly.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PlotlyXs>`
- `<$PlotlySm>`
- `<$PlotlyMd>`
- `<$PlotlyLg>`





## Plotly

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Plotly
include('simpleicons-8/P/Plotly')

' renders the element
Plotly('Plotly', 'Plotly', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Plotly
include('simpleicons-8/P/Plotly')

' renders the element
Plotly('Plotly', 'Plotly', 'an optional tech label', 'an optional description')
@enduml
```

