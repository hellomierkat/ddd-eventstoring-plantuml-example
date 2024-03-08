# HelpCenter


```text
material-4/Action/HelpCenter
```

```text
include('material-4/Action/HelpCenter')
```



| Illustration | HelpCenter |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/HelpCenter.png) | ![illustration for HelpCenter](../../material-4/Action/HelpCenter.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HelpCenterXs>`
- `<$HelpCenterSm>`
- `<$HelpCenterMd>`
- `<$HelpCenterLg>`





## HelpCenter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element HelpCenter
include('material-4/Action/HelpCenter')

' renders the element
HelpCenter('HelpCenter', 'Help Center', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HelpCenter
include('material-4/Action/HelpCenter')

' renders the element
HelpCenter('HelpCenter', 'Help Center', 'an optional tech label', 'an optional description')
@enduml
```

