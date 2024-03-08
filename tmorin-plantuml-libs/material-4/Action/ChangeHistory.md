# ChangeHistory


```text
material-4/Action/ChangeHistory
```

```text
include('material-4/Action/ChangeHistory')
```



| Illustration | ChangeHistory |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/ChangeHistory.png) | ![illustration for ChangeHistory](../../material-4/Action/ChangeHistory.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ChangeHistoryXs>`
- `<$ChangeHistorySm>`
- `<$ChangeHistoryMd>`
- `<$ChangeHistoryLg>`





## ChangeHistory

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ChangeHistory
include('material-4/Action/ChangeHistory')

' renders the element
ChangeHistory('ChangeHistory', 'Change History', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ChangeHistory
include('material-4/Action/ChangeHistory')

' renders the element
ChangeHistory('ChangeHistory', 'Change History', 'an optional tech label', 'an optional description')
@enduml
```

