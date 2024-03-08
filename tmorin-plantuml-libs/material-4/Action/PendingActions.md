# PendingActions


```text
material-4/Action/PendingActions
```

```text
include('material-4/Action/PendingActions')
```



| Illustration | PendingActions |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/PendingActions.png) | ![illustration for PendingActions](../../material-4/Action/PendingActions.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PendingActionsXs>`
- `<$PendingActionsSm>`
- `<$PendingActionsMd>`
- `<$PendingActionsLg>`





## PendingActions

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PendingActions
include('material-4/Action/PendingActions')

' renders the element
PendingActions('PendingActions', 'Pending Actions', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PendingActions
include('material-4/Action/PendingActions')

' renders the element
PendingActions('PendingActions', 'Pending Actions', 'an optional tech label', 'an optional description')
@enduml
```

