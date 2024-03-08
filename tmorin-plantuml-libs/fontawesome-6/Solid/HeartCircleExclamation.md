# HeartCircleExclamation


```text
fontawesome-6/Solid/HeartCircleExclamation
```

```text
include('fontawesome-6/Solid/HeartCircleExclamation')
```



| Illustration | HeartCircleExclamation |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/HeartCircleExclamation.png) | ![illustration for HeartCircleExclamation](../../fontawesome-6/Solid/HeartCircleExclamation.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HeartCircleExclamationXs>`
- `<$HeartCircleExclamationSm>`
- `<$HeartCircleExclamationMd>`
- `<$HeartCircleExclamationLg>`





## HeartCircleExclamation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element HeartCircleExclamation
include('fontawesome-6/Solid/HeartCircleExclamation')

' renders the element
HeartCircleExclamation('HeartCircleExclamation', 'Heart Circle Exclamation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HeartCircleExclamation
include('fontawesome-6/Solid/HeartCircleExclamation')

' renders the element
HeartCircleExclamation('HeartCircleExclamation', 'Heart Circle Exclamation', 'an optional tech label', 'an optional description')
@enduml
```

