# South


```text
material-4/Navigation/South
```

```text
include('material-4/Navigation/South')
```



| Illustration | South |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/South.png) | ![illustration for South](../../material-4/Navigation/South.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SouthXs>`
- `<$SouthSm>`
- `<$SouthMd>`
- `<$SouthLg>`





## South

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element South
include('material-4/Navigation/South')

' renders the element
South('South', 'South', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element South
include('material-4/Navigation/South')

' renders the element
South('South', 'South', 'an optional tech label', 'an optional description')
@enduml
```

