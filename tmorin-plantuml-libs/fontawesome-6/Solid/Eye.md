# Eye


```text
fontawesome-6/Solid/Eye
```

```text
include('fontawesome-6/Solid/Eye')
```



| Illustration | Eye |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Eye.png) | ![illustration for Eye](../../fontawesome-6/Solid/Eye.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EyeXs>`
- `<$EyeSm>`
- `<$EyeMd>`
- `<$EyeLg>`





## Eye

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Eye
include('fontawesome-6/Solid/Eye')

' renders the element
Eye('Eye', 'Eye', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Eye
include('fontawesome-6/Solid/Eye')

' renders the element
Eye('Eye', 'Eye', 'an optional tech label', 'an optional description')
@enduml
```

