# AppRegistration


```text
material-4/Communication/AppRegistration
```

```text
include('material-4/Communication/AppRegistration')
```



| Illustration | AppRegistration |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/AppRegistration.png) | ![illustration for AppRegistration](../../material-4/Communication/AppRegistration.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AppRegistrationXs>`
- `<$AppRegistrationSm>`
- `<$AppRegistrationMd>`
- `<$AppRegistrationLg>`





## AppRegistration

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AppRegistration
include('material-4/Communication/AppRegistration')

' renders the element
AppRegistration('AppRegistration', 'App Registration', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element AppRegistration
include('material-4/Communication/AppRegistration')

' renders the element
AppRegistration('AppRegistration', 'App Registration', 'an optional tech label', 'an optional description')
@enduml
```

