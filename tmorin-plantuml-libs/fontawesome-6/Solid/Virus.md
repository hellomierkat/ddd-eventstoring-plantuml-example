# Virus


```text
fontawesome-6/Solid/Virus
```

```text
include('fontawesome-6/Solid/Virus')
```



| Illustration | Virus |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Virus.png) | ![illustration for Virus](../../fontawesome-6/Solid/Virus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VirusXs>`
- `<$VirusSm>`
- `<$VirusMd>`
- `<$VirusLg>`





## Virus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Virus
include('fontawesome-6/Solid/Virus')

' renders the element
Virus('Virus', 'Virus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Virus
include('fontawesome-6/Solid/Virus')

' renders the element
Virus('Virus', 'Virus', 'an optional tech label', 'an optional description')
@enduml
```

