# BeachAccess


```text
material-4/Places/BeachAccess
```

```text
include('material-4/Places/BeachAccess')
```



| Illustration | BeachAccess |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/BeachAccess.png) | ![illustration for BeachAccess](../../material-4/Places/BeachAccess.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BeachAccessXs>`
- `<$BeachAccessSm>`
- `<$BeachAccessMd>`
- `<$BeachAccessLg>`





## BeachAccess

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element BeachAccess
include('material-4/Places/BeachAccess')

' renders the element
BeachAccess('BeachAccess', 'Beach Access', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BeachAccess
include('material-4/Places/BeachAccess')

' renders the element
BeachAccess('BeachAccess', 'Beach Access', 'an optional tech label', 'an optional description')
@enduml
```

