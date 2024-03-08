# ToggleOn


```text
fontawesome-6/Solid/ToggleOn
```

```text
include('fontawesome-6/Solid/ToggleOn')
```



| Illustration | ToggleOn |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ToggleOn.png) | ![illustration for ToggleOn](../../fontawesome-6/Solid/ToggleOn.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ToggleOnXs>`
- `<$ToggleOnSm>`
- `<$ToggleOnMd>`
- `<$ToggleOnLg>`





## ToggleOn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ToggleOn
include('fontawesome-6/Solid/ToggleOn')

' renders the element
ToggleOn('ToggleOn', 'Toggle On', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ToggleOn
include('fontawesome-6/Solid/ToggleOn')

' renders the element
ToggleOn('ToggleOn', 'Toggle On', 'an optional tech label', 'an optional description')
@enduml
```

