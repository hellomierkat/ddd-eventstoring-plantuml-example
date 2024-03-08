# Dove


```text
fontawesome-6/Solid/Dove
```

```text
include('fontawesome-6/Solid/Dove')
```



| Illustration | Dove |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Dove.png) | ![illustration for Dove](../../fontawesome-6/Solid/Dove.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DoveXs>`
- `<$DoveSm>`
- `<$DoveMd>`
- `<$DoveLg>`





## Dove

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Dove
include('fontawesome-6/Solid/Dove')

' renders the element
Dove('Dove', 'Dove', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Dove
include('fontawesome-6/Solid/Dove')

' renders the element
Dove('Dove', 'Dove', 'an optional tech label', 'an optional description')
@enduml
```

