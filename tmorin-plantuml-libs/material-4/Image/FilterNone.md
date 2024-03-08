# FilterNone


```text
material-4/Image/FilterNone
```

```text
include('material-4/Image/FilterNone')
```



| Illustration | FilterNone |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/FilterNone.png) | ![illustration for FilterNone](../../material-4/Image/FilterNone.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FilterNoneXs>`
- `<$FilterNoneSm>`
- `<$FilterNoneMd>`
- `<$FilterNoneLg>`





## FilterNone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FilterNone
include('material-4/Image/FilterNone')

' renders the element
FilterNone('FilterNone', 'Filter None', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FilterNone
include('material-4/Image/FilterNone')

' renders the element
FilterNone('FilterNone', 'Filter None', 'an optional tech label', 'an optional description')
@enduml
```

