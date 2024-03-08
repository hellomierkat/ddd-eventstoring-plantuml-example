# TrendingDown


```text
material-4/Action/TrendingDown
```

```text
include('material-4/Action/TrendingDown')
```



| Illustration | TrendingDown |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/TrendingDown.png) | ![illustration for TrendingDown](../../material-4/Action/TrendingDown.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TrendingDownXs>`
- `<$TrendingDownSm>`
- `<$TrendingDownMd>`
- `<$TrendingDownLg>`





## TrendingDown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element TrendingDown
include('material-4/Action/TrendingDown')

' renders the element
TrendingDown('TrendingDown', 'Trending Down', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TrendingDown
include('material-4/Action/TrendingDown')

' renders the element
TrendingDown('TrendingDown', 'Trending Down', 'an optional tech label', 'an optional description')
@enduml
```

