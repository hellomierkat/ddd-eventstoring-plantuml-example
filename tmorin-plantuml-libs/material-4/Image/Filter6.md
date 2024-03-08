# Filter6


```text
material-4/Image/Filter6
```

```text
include('material-4/Image/Filter6')
```



| Illustration | Filter6 |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Filter6.png) | ![illustration for Filter6](../../material-4/Image/Filter6.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Filter6Xs>`
- `<$Filter6Sm>`
- `<$Filter6Md>`
- `<$Filter6Lg>`





## Filter6

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Filter6
include('material-4/Image/Filter6')

' renders the element
Filter6('Filter6', 'Filter6', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Filter6
include('material-4/Image/Filter6')

' renders the element
Filter6('Filter6', 'Filter6', 'an optional tech label', 'an optional description')
@enduml
```

