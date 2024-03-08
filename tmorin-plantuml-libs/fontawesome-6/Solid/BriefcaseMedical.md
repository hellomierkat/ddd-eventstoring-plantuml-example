# BriefcaseMedical


```text
fontawesome-6/Solid/BriefcaseMedical
```

```text
include('fontawesome-6/Solid/BriefcaseMedical')
```



| Illustration | BriefcaseMedical |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BriefcaseMedical.png) | ![illustration for BriefcaseMedical](../../fontawesome-6/Solid/BriefcaseMedical.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BriefcaseMedicalXs>`
- `<$BriefcaseMedicalSm>`
- `<$BriefcaseMedicalMd>`
- `<$BriefcaseMedicalLg>`





## BriefcaseMedical

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BriefcaseMedical
include('fontawesome-6/Solid/BriefcaseMedical')

' renders the element
BriefcaseMedical('BriefcaseMedical', 'Briefcase Medical', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BriefcaseMedical
include('fontawesome-6/Solid/BriefcaseMedical')

' renders the element
BriefcaseMedical('BriefcaseMedical', 'Briefcase Medical', 'an optional tech label', 'an optional description')
@enduml
```

