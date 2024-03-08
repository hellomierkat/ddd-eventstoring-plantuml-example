# SyncAlt


```text
material-4/Action/SyncAlt
```

```text
include('material-4/Action/SyncAlt')
```



| Illustration | SyncAlt |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/SyncAlt.png) | ![illustration for SyncAlt](../../material-4/Action/SyncAlt.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SyncAltXs>`
- `<$SyncAltSm>`
- `<$SyncAltMd>`
- `<$SyncAltLg>`





## SyncAlt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SyncAlt
include('material-4/Action/SyncAlt')

' renders the element
SyncAlt('SyncAlt', 'Sync Alt', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SyncAlt
include('material-4/Action/SyncAlt')

' renders the element
SyncAlt('SyncAlt', 'Sync Alt', 'an optional tech label', 'an optional description')
@enduml
```

