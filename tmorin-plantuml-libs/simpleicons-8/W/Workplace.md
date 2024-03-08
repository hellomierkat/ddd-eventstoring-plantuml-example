# Workplace


```text
simpleicons-8/W/Workplace
```

```text
include('simpleicons-8/W/Workplace')
```



| Illustration | Workplace |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/W/Workplace.png) | ![illustration for Workplace](../../simpleicons-8/W/Workplace.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WorkplaceXs>`
- `<$WorkplaceSm>`
- `<$WorkplaceMd>`
- `<$WorkplaceLg>`





## Workplace

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Workplace
include('simpleicons-8/W/Workplace')

' renders the element
Workplace('Workplace', 'Workplace', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Workplace
include('simpleicons-8/W/Workplace')

' renders the element
Workplace('Workplace', 'Workplace', 'an optional tech label', 'an optional description')
@enduml
```

