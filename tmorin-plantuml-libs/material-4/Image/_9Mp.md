# _9Mp


```text
material-4/Image/_9Mp
```

```text
include('material-4/Image/_9Mp')
```



| Illustration | _9Mp |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/_9Mp.png) | ![illustration for _9Mp](../../material-4/Image/_9Mp.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$_9MpXs>`
- `<$_9MpSm>`
- `<$_9MpMd>`
- `<$_9MpLg>`





## _9Mp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element _9Mp
include('material-4/Image/_9Mp')

' renders the element
_9Mp('9mp', '9mp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element _9Mp
include('material-4/Image/_9Mp')

' renders the element
_9Mp('9mp', '9mp', 'an optional tech label', 'an optional description')
@enduml
```

