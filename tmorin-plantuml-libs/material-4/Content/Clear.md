# Clear


```text
material-4/Content/Clear
```

```text
include('material-4/Content/Clear')
```



| Illustration | Clear |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Clear.png) | ![illustration for Clear](../../material-4/Content/Clear.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ClearXs>`
- `<$ClearSm>`
- `<$ClearMd>`
- `<$ClearLg>`





## Clear

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Clear
include('material-4/Content/Clear')

' renders the element
Clear('Clear', 'Clear', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Clear
include('material-4/Content/Clear')

' renders the element
Clear('Clear', 'Clear', 'an optional tech label', 'an optional description')
@enduml
```

