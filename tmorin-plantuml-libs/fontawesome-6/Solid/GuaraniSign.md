# GuaraniSign


```text
fontawesome-6/Solid/GuaraniSign
```

```text
include('fontawesome-6/Solid/GuaraniSign')
```



| Illustration | GuaraniSign |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/GuaraniSign.png) | ![illustration for GuaraniSign](../../fontawesome-6/Solid/GuaraniSign.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GuaraniSignXs>`
- `<$GuaraniSignSm>`
- `<$GuaraniSignMd>`
- `<$GuaraniSignLg>`





## GuaraniSign

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GuaraniSign
include('fontawesome-6/Solid/GuaraniSign')

' renders the element
GuaraniSign('GuaraniSign', 'Guarani Sign', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element GuaraniSign
include('fontawesome-6/Solid/GuaraniSign')

' renders the element
GuaraniSign('GuaraniSign', 'Guarani Sign', 'an optional tech label', 'an optional description')
@enduml
```

