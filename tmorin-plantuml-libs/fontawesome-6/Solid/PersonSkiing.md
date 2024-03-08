# PersonSkiing


```text
fontawesome-6/Solid/PersonSkiing
```

```text
include('fontawesome-6/Solid/PersonSkiing')
```



| Illustration | PersonSkiing |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PersonSkiing.png) | ![illustration for PersonSkiing](../../fontawesome-6/Solid/PersonSkiing.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PersonSkiingXs>`
- `<$PersonSkiingSm>`
- `<$PersonSkiingMd>`
- `<$PersonSkiingLg>`





## PersonSkiing

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PersonSkiing
include('fontawesome-6/Solid/PersonSkiing')

' renders the element
PersonSkiing('PersonSkiing', 'Person Skiing', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonSkiing
include('fontawesome-6/Solid/PersonSkiing')

' renders the element
PersonSkiing('PersonSkiing', 'Person Skiing', 'an optional tech label', 'an optional description')
@enduml
```

