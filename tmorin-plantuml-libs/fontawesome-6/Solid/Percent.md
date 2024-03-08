# Percent


```text
fontawesome-6/Solid/Percent
```

```text
include('fontawesome-6/Solid/Percent')
```



| Illustration | Percent |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Percent.png) | ![illustration for Percent](../../fontawesome-6/Solid/Percent.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PercentXs>`
- `<$PercentSm>`
- `<$PercentMd>`
- `<$PercentLg>`





## Percent

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Percent
include('fontawesome-6/Solid/Percent')

' renders the element
Percent('Percent', 'Percent', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Percent
include('fontawesome-6/Solid/Percent')

' renders the element
Percent('Percent', 'Percent', 'an optional tech label', 'an optional description')
@enduml
```

