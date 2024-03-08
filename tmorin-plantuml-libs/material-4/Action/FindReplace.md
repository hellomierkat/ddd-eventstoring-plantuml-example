# FindReplace


```text
material-4/Action/FindReplace
```

```text
include('material-4/Action/FindReplace')
```



| Illustration | FindReplace |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/FindReplace.png) | ![illustration for FindReplace](../../material-4/Action/FindReplace.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FindReplaceXs>`
- `<$FindReplaceSm>`
- `<$FindReplaceMd>`
- `<$FindReplaceLg>`





## FindReplace

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FindReplace
include('material-4/Action/FindReplace')

' renders the element
FindReplace('FindReplace', 'Find Replace', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FindReplace
include('material-4/Action/FindReplace')

' renders the element
FindReplace('FindReplace', 'Find Replace', 'an optional tech label', 'an optional description')
@enduml
```

