# Sync


```text
material-4/Notification/Sync
```

```text
include('material-4/Notification/Sync')
```



| Illustration | Sync |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Notification/Sync.png) | ![illustration for Sync](../../material-4/Notification/Sync.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SyncXs>`
- `<$SyncSm>`
- `<$SyncMd>`
- `<$SyncLg>`





## Sync

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Sync
include('material-4/Notification/Sync')

' renders the element
Sync('Sync', 'Sync', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sync
include('material-4/Notification/Sync')

' renders the element
Sync('Sync', 'Sync', 'an optional tech label', 'an optional description')
@enduml
```

