# ChartPie


```text
fontawesome-6/Solid/ChartPie
```

```text
include('fontawesome-6/Solid/ChartPie')
```



| Illustration | ChartPie |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ChartPie.png) | ![illustration for ChartPie](../../fontawesome-6/Solid/ChartPie.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ChartPieXs>`
- `<$ChartPieSm>`
- `<$ChartPieMd>`
- `<$ChartPieLg>`





## ChartPie

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ChartPie
include('fontawesome-6/Solid/ChartPie')

' renders the element
ChartPie('ChartPie', 'Chart Pie', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChartPie
include('fontawesome-6/Solid/ChartPie')

' renders the element
ChartPie('ChartPie', 'Chart Pie', 'an optional tech label', 'an optional description')
@enduml
```

