# SettingsCell


```text
material-4/Action/SettingsCell
```

```text
include('material-4/Action/SettingsCell')
```



| Illustration | SettingsCell |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/SettingsCell.png) | ![illustration for SettingsCell](../../material-4/Action/SettingsCell.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SettingsCellXs>`
- `<$SettingsCellSm>`
- `<$SettingsCellMd>`
- `<$SettingsCellLg>`





## SettingsCell

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SettingsCell
include('material-4/Action/SettingsCell')

' renders the element
SettingsCell('SettingsCell', 'Settings Cell', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SettingsCell
include('material-4/Action/SettingsCell')

' renders the element
SettingsCell('SettingsCell', 'Settings Cell', 'an optional tech label', 'an optional description')
@enduml
```

