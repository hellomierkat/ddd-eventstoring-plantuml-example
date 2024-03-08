# Empire


```text
fontawesome-6/Brands/Empire
```

```text
include('fontawesome-6/Brands/Empire')
```



| Illustration | Empire |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Empire.png) | ![illustration for Empire](../../fontawesome-6/Brands/Empire.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EmpireXs>`
- `<$EmpireSm>`
- `<$EmpireMd>`
- `<$EmpireLg>`





## Empire

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Empire
include('fontawesome-6/Brands/Empire')

' renders the element
Empire('Empire', 'Empire', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Empire
include('fontawesome-6/Brands/Empire')

' renders the element
Empire('Empire', 'Empire', 'an optional tech label', 'an optional description')
@enduml
```

