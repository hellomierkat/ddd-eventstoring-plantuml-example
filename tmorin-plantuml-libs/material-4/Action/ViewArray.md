# ViewArray


```text
material-4/Action/ViewArray
```

```text
include('material-4/Action/ViewArray')
```



| Illustration | ViewArray |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/ViewArray.png) | ![illustration for ViewArray](../../material-4/Action/ViewArray.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ViewArrayXs>`
- `<$ViewArraySm>`
- `<$ViewArrayMd>`
- `<$ViewArrayLg>`





## ViewArray

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ViewArray
include('material-4/Action/ViewArray')

' renders the element
ViewArray('ViewArray', 'View Array', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ViewArray
include('material-4/Action/ViewArray')

' renders the element
ViewArray('ViewArray', 'View Array', 'an optional tech label', 'an optional description')
@enduml
```

