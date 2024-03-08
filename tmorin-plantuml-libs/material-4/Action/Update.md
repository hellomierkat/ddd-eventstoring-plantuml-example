# Update


```text
material-4/Action/Update
```

```text
include('material-4/Action/Update')
```



| Illustration | Update |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Update.png) | ![illustration for Update](../../material-4/Action/Update.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$UpdateXs>`
- `<$UpdateSm>`
- `<$UpdateMd>`
- `<$UpdateLg>`





## Update

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Update
include('material-4/Action/Update')

' renders the element
Update('Update', 'Update', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Update
include('material-4/Action/Update')

' renders the element
Update('Update', 'Update', 'an optional tech label', 'an optional description')
@enduml
```

