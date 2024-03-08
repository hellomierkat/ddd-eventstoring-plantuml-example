# DoNotStep


```text
material-4/Places/DoNotStep
```

```text
include('material-4/Places/DoNotStep')
```



| Illustration | DoNotStep |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/DoNotStep.png) | ![illustration for DoNotStep](../../material-4/Places/DoNotStep.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DoNotStepXs>`
- `<$DoNotStepSm>`
- `<$DoNotStepMd>`
- `<$DoNotStepLg>`





## DoNotStep

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DoNotStep
include('material-4/Places/DoNotStep')

' renders the element
DoNotStep('DoNotStep', 'Do Not Step', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DoNotStep
include('material-4/Places/DoNotStep')

' renders the element
DoNotStep('DoNotStep', 'Do Not Step', 'an optional tech label', 'an optional description')
@enduml
```

