# Weekend


```text
material-4/Content/Weekend
```

```text
include('material-4/Content/Weekend')
```



| Illustration | Weekend |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Weekend.png) | ![illustration for Weekend](../../material-4/Content/Weekend.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WeekendXs>`
- `<$WeekendSm>`
- `<$WeekendMd>`
- `<$WeekendLg>`





## Weekend

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Weekend
include('material-4/Content/Weekend')

' renders the element
Weekend('Weekend', 'Weekend', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Weekend
include('material-4/Content/Weekend')

' renders the element
Weekend('Weekend', 'Weekend', 'an optional tech label', 'an optional description')
@enduml
```

