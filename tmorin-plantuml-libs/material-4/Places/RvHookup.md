# RvHookup


```text
material-4/Places/RvHookup
```

```text
include('material-4/Places/RvHookup')
```



| Illustration | RvHookup |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/RvHookup.png) | ![illustration for RvHookup](../../material-4/Places/RvHookup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RvHookupXs>`
- `<$RvHookupSm>`
- `<$RvHookupMd>`
- `<$RvHookupLg>`





## RvHookup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element RvHookup
include('material-4/Places/RvHookup')

' renders the element
RvHookup('RvHookup', 'Rv Hookup', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element RvHookup
include('material-4/Places/RvHookup')

' renders the element
RvHookup('RvHookup', 'Rv Hookup', 'an optional tech label', 'an optional description')
@enduml
```

