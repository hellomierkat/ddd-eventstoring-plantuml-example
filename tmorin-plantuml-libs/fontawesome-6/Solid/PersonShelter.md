# PersonShelter


```text
fontawesome-6/Solid/PersonShelter
```

```text
include('fontawesome-6/Solid/PersonShelter')
```



| Illustration | PersonShelter |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PersonShelter.png) | ![illustration for PersonShelter](../../fontawesome-6/Solid/PersonShelter.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PersonShelterXs>`
- `<$PersonShelterSm>`
- `<$PersonShelterMd>`
- `<$PersonShelterLg>`





## PersonShelter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PersonShelter
include('fontawesome-6/Solid/PersonShelter')

' renders the element
PersonShelter('PersonShelter', 'Person Shelter', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PersonShelter
include('fontawesome-6/Solid/PersonShelter')

' renders the element
PersonShelter('PersonShelter', 'Person Shelter', 'an optional tech label', 'an optional description')
@enduml
```

