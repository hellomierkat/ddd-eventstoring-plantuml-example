# AddBox


```text
material-4/Content/AddBox
```

```text
include('material-4/Content/AddBox')
```



| Illustration | AddBox |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/AddBox.png) | ![illustration for AddBox](../../material-4/Content/AddBox.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddBoxXs>`
- `<$AddBoxSm>`
- `<$AddBoxMd>`
- `<$AddBoxLg>`





## AddBox

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AddBox
include('material-4/Content/AddBox')

' renders the element
AddBox('AddBox', 'Add Box', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AddBox
include('material-4/Content/AddBox')

' renders the element
AddBox('AddBox', 'Add Box', 'an optional tech label', 'an optional description')
@enduml
```

