# Globe


```text
fontawesome-6/Solid/Globe
```

```text
include('fontawesome-6/Solid/Globe')
```



| Illustration | Globe |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Globe.png) | ![illustration for Globe](../../fontawesome-6/Solid/Globe.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GlobeXs>`
- `<$GlobeSm>`
- `<$GlobeMd>`
- `<$GlobeLg>`





## Globe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Globe
include('fontawesome-6/Solid/Globe')

' renders the element
Globe('Globe', 'Globe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Globe
include('fontawesome-6/Solid/Globe')

' renders the element
Globe('Globe', 'Globe', 'an optional tech label', 'an optional description')
@enduml
```

