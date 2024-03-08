# HistoryToggleOff


```text
material-4/Action/HistoryToggleOff
```

```text
include('material-4/Action/HistoryToggleOff')
```



| Illustration | HistoryToggleOff |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/HistoryToggleOff.png) | ![illustration for HistoryToggleOff](../../material-4/Action/HistoryToggleOff.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HistoryToggleOffXs>`
- `<$HistoryToggleOffSm>`
- `<$HistoryToggleOffMd>`
- `<$HistoryToggleOffLg>`





## HistoryToggleOff

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element HistoryToggleOff
include('material-4/Action/HistoryToggleOff')

' renders the element
HistoryToggleOff('HistoryToggleOff', 'History Toggle Off', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HistoryToggleOff
include('material-4/Action/HistoryToggleOff')

' renders the element
HistoryToggleOff('HistoryToggleOff', 'History Toggle Off', 'an optional tech label', 'an optional description')
@enduml
```

