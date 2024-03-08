# Report


```text
material-4/Content/Report
```

```text
include('material-4/Content/Report')
```



| Illustration | Report |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Report.png) | ![illustration for Report](../../material-4/Content/Report.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReportXs>`
- `<$ReportSm>`
- `<$ReportMd>`
- `<$ReportLg>`





## Report

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Report
include('material-4/Content/Report')

' renders the element
Report('Report', 'Report', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Report
include('material-4/Content/Report')

' renders the element
Report('Report', 'Report', 'an optional tech label', 'an optional description')
@enduml
```

