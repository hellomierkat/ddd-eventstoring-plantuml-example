# ArrowDownward


```text
material-4/Navigation/ArrowDownward
```

```text
include('material-4/Navigation/ArrowDownward')
```



| Illustration | ArrowDownward |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/ArrowDownward.png) | ![illustration for ArrowDownward](../../material-4/Navigation/ArrowDownward.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ArrowDownwardXs>`
- `<$ArrowDownwardSm>`
- `<$ArrowDownwardMd>`
- `<$ArrowDownwardLg>`





## ArrowDownward

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ArrowDownward
include('material-4/Navigation/ArrowDownward')

' renders the element
ArrowDownward('ArrowDownward', 'Arrow Downward', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ArrowDownward
include('material-4/Navigation/ArrowDownward')

' renders the element
ArrowDownward('ArrowDownward', 'Arrow Downward', 'an optional tech label', 'an optional description')
@enduml
```

