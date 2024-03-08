# CloudArrowUp


```text
fontawesome-6/Solid/CloudArrowUp
```

```text
include('fontawesome-6/Solid/CloudArrowUp')
```



| Illustration | CloudArrowUp |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/CloudArrowUp.png) | ![illustration for CloudArrowUp](../../fontawesome-6/Solid/CloudArrowUp.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CloudArrowUpXs>`
- `<$CloudArrowUpSm>`
- `<$CloudArrowUpMd>`
- `<$CloudArrowUpLg>`





## CloudArrowUp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CloudArrowUp
include('fontawesome-6/Solid/CloudArrowUp')

' renders the element
CloudArrowUp('CloudArrowUp', 'Cloud Arrow Up', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CloudArrowUp
include('fontawesome-6/Solid/CloudArrowUp')

' renders the element
CloudArrowUp('CloudArrowUp', 'Cloud Arrow Up', 'an optional tech label', 'an optional description')
@enduml
```

