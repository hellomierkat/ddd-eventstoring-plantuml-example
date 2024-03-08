# Bold


```text
fontawesome-6/Solid/Bold
```

```text
include('fontawesome-6/Solid/Bold')
```



| Illustration | Bold |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Bold.png) | ![illustration for Bold](../../fontawesome-6/Solid/Bold.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BoldXs>`
- `<$BoldSm>`
- `<$BoldMd>`
- `<$BoldLg>`





## Bold

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Bold
include('fontawesome-6/Solid/Bold')

' renders the element
Bold('Bold', 'Bold', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bold
include('fontawesome-6/Solid/Bold')

' renders the element
Bold('Bold', 'Bold', 'an optional tech label', 'an optional description')
@enduml
```

