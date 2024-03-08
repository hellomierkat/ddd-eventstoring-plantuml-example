# WbIncandescent


```text
material-4/Image/WbIncandescent
```

```text
include('material-4/Image/WbIncandescent')
```



| Illustration | WbIncandescent |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/WbIncandescent.png) | ![illustration for WbIncandescent](../../material-4/Image/WbIncandescent.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WbIncandescentXs>`
- `<$WbIncandescentSm>`
- `<$WbIncandescentMd>`
- `<$WbIncandescentLg>`





## WbIncandescent

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element WbIncandescent
include('material-4/Image/WbIncandescent')

' renders the element
WbIncandescent('WbIncandescent', 'Wb Incandescent', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element WbIncandescent
include('material-4/Image/WbIncandescent')

' renders the element
WbIncandescent('WbIncandescent', 'Wb Incandescent', 'an optional tech label', 'an optional description')
@enduml
```

