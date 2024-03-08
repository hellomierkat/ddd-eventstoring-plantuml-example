# SuitcaseMedical


```text
fontawesome-6/Solid/SuitcaseMedical
```

```text
include('fontawesome-6/Solid/SuitcaseMedical')
```



| Illustration | SuitcaseMedical |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/SuitcaseMedical.png) | ![illustration for SuitcaseMedical](../../fontawesome-6/Solid/SuitcaseMedical.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SuitcaseMedicalXs>`
- `<$SuitcaseMedicalSm>`
- `<$SuitcaseMedicalMd>`
- `<$SuitcaseMedicalLg>`





## SuitcaseMedical

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element SuitcaseMedical
include('fontawesome-6/Solid/SuitcaseMedical')

' renders the element
SuitcaseMedical('SuitcaseMedical', 'Suitcase Medical', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SuitcaseMedical
include('fontawesome-6/Solid/SuitcaseMedical')

' renders the element
SuitcaseMedical('SuitcaseMedical', 'Suitcase Medical', 'an optional tech label', 'an optional description')
@enduml
```

