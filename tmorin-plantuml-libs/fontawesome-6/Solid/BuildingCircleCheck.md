# BuildingCircleCheck


```text
fontawesome-6/Solid/BuildingCircleCheck
```

```text
include('fontawesome-6/Solid/BuildingCircleCheck')
```



| Illustration | BuildingCircleCheck |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BuildingCircleCheck.png) | ![illustration for BuildingCircleCheck](../../fontawesome-6/Solid/BuildingCircleCheck.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BuildingCircleCheckXs>`
- `<$BuildingCircleCheckSm>`
- `<$BuildingCircleCheckMd>`
- `<$BuildingCircleCheckLg>`





## BuildingCircleCheck

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BuildingCircleCheck
include('fontawesome-6/Solid/BuildingCircleCheck')

' renders the element
BuildingCircleCheck('BuildingCircleCheck', 'Building Circle Check', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BuildingCircleCheck
include('fontawesome-6/Solid/BuildingCircleCheck')

' renders the element
BuildingCircleCheck('BuildingCircleCheck', 'Building Circle Check', 'an optional tech label', 'an optional description')
@enduml
```

