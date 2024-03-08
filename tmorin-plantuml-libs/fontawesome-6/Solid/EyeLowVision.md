# EyeLowVision


```text
fontawesome-6/Solid/EyeLowVision
```

```text
include('fontawesome-6/Solid/EyeLowVision')
```



| Illustration | EyeLowVision |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/EyeLowVision.png) | ![illustration for EyeLowVision](../../fontawesome-6/Solid/EyeLowVision.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EyeLowVisionXs>`
- `<$EyeLowVisionSm>`
- `<$EyeLowVisionMd>`
- `<$EyeLowVisionLg>`





## EyeLowVision

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element EyeLowVision
include('fontawesome-6/Solid/EyeLowVision')

' renders the element
EyeLowVision('EyeLowVision', 'Eye Low Vision', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element EyeLowVision
include('fontawesome-6/Solid/EyeLowVision')

' renders the element
EyeLowVision('EyeLowVision', 'Eye Low Vision', 'an optional tech label', 'an optional description')
@enduml
```

