# _3Mp


```text
material-4/Image/_3Mp
```

```text
include('material-4/Image/_3Mp')
```



| Illustration | _3Mp |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/_3Mp.png) | ![illustration for _3Mp](../../material-4/Image/_3Mp.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$_3MpXs>`
- `<$_3MpSm>`
- `<$_3MpMd>`
- `<$_3MpLg>`





## _3Mp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element _3Mp
include('material-4/Image/_3Mp')

' renders the element
_3Mp('3mp', '3mp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element _3Mp
include('material-4/Image/_3Mp')

' renders the element
_3Mp('3mp', '3mp', 'an optional tech label', 'an optional description')
@enduml
```

