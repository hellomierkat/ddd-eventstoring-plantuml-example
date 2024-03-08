# Lightbulb


```text
fontawesome-6/Regular/Lightbulb
```

```text
include('fontawesome-6/Regular/Lightbulb')
```



| Illustration | Lightbulb |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/Lightbulb.png) | ![illustration for Lightbulb](../../fontawesome-6/Regular/Lightbulb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LightbulbXs>`
- `<$LightbulbSm>`
- `<$LightbulbMd>`
- `<$LightbulbLg>`





## Lightbulb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Lightbulb
include('fontawesome-6/Regular/Lightbulb')

' renders the element
Lightbulb('Lightbulb', 'Lightbulb', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Lightbulb
include('fontawesome-6/Regular/Lightbulb')

' renders the element
Lightbulb('Lightbulb', 'Lightbulb', 'an optional tech label', 'an optional description')
@enduml
```

