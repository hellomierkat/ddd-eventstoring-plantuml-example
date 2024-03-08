# CarOn


```text
fontawesome-6/Solid/CarOn
```

```text
include('fontawesome-6/Solid/CarOn')
```



| Illustration | CarOn |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/CarOn.png) | ![illustration for CarOn](../../fontawesome-6/Solid/CarOn.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CarOnXs>`
- `<$CarOnSm>`
- `<$CarOnMd>`
- `<$CarOnLg>`





## CarOn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CarOn
include('fontawesome-6/Solid/CarOn')

' renders the element
CarOn('CarOn', 'Car On', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CarOn
include('fontawesome-6/Solid/CarOn')

' renders the element
CarOn('CarOn', 'Car On', 'an optional tech label', 'an optional description')
@enduml
```

