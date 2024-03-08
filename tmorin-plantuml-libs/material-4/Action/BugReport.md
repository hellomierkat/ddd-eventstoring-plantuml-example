# BugReport


```text
material-4/Action/BugReport
```

```text
include('material-4/Action/BugReport')
```



| Illustration | BugReport |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/BugReport.png) | ![illustration for BugReport](../../material-4/Action/BugReport.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BugReportXs>`
- `<$BugReportSm>`
- `<$BugReportMd>`
- `<$BugReportLg>`





## BugReport

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BugReport
include('material-4/Action/BugReport')

' renders the element
BugReport('BugReport', 'Bug Report', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BugReport
include('material-4/Action/BugReport')

' renders the element
BugReport('BugReport', 'Bug Report', 'an optional tech label', 'an optional description')
@enduml
```

