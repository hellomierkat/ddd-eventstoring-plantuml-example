# StackedBarChart


```text
material-4/Content/StackedBarChart
```

```text
include('material-4/Content/StackedBarChart')
```



| Illustration | StackedBarChart |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/StackedBarChart.png) | ![illustration for StackedBarChart](../../material-4/Content/StackedBarChart.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$StackedBarChartXs>`
- `<$StackedBarChartSm>`
- `<$StackedBarChartMd>`
- `<$StackedBarChartLg>`





## StackedBarChart

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element StackedBarChart
include('material-4/Content/StackedBarChart')

' renders the element
StackedBarChart('StackedBarChart', 'Stacked Bar Chart', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element StackedBarChart
include('material-4/Content/StackedBarChart')

' renders the element
StackedBarChart('StackedBarChart', 'Stacked Bar Chart', 'an optional tech label', 'an optional description')
@enduml
```

