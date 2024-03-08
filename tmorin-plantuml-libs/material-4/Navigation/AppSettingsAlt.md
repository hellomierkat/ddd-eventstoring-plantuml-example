# AppSettingsAlt


```text
material-4/Navigation/AppSettingsAlt
```

```text
include('material-4/Navigation/AppSettingsAlt')
```



| Illustration | AppSettingsAlt |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/AppSettingsAlt.png) | ![illustration for AppSettingsAlt](../../material-4/Navigation/AppSettingsAlt.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AppSettingsAltXs>`
- `<$AppSettingsAltSm>`
- `<$AppSettingsAltMd>`
- `<$AppSettingsAltLg>`





## AppSettingsAlt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AppSettingsAlt
include('material-4/Navigation/AppSettingsAlt')

' renders the element
AppSettingsAlt('AppSettingsAlt', 'App Settings Alt', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AppSettingsAlt
include('material-4/Navigation/AppSettingsAlt')

' renders the element
AppSettingsAlt('AppSettingsAlt', 'App Settings Alt', 'an optional tech label', 'an optional description')
@enduml
```
