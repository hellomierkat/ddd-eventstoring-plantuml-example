# Locust


```text
fontawesome-6/Solid/Locust
```

```text
include('fontawesome-6/Solid/Locust')
```



| Illustration | Locust |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Locust.png) | ![illustration for Locust](../../fontawesome-6/Solid/Locust.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LocustXs>`
- `<$LocustSm>`
- `<$LocustMd>`
- `<$LocustLg>`





## Locust

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Locust
include('fontawesome-6/Solid/Locust')

' renders the element
Locust('Locust', 'Locust', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Locust
include('fontawesome-6/Solid/Locust')

' renders the element
Locust('Locust', 'Locust', 'an optional tech label', 'an optional description')
@enduml
```

