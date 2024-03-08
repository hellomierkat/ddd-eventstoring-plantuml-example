# TheRedYeti


```text
fontawesome-6/Brands/TheRedYeti
```

```text
include('fontawesome-6/Brands/TheRedYeti')
```



| Illustration | TheRedYeti |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/TheRedYeti.png) | ![illustration for TheRedYeti](../../fontawesome-6/Brands/TheRedYeti.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TheRedYetiXs>`
- `<$TheRedYetiSm>`
- `<$TheRedYetiMd>`
- `<$TheRedYetiLg>`





## TheRedYeti

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TheRedYeti
include('fontawesome-6/Brands/TheRedYeti')

' renders the element
TheRedYeti('TheRedYeti', 'The Red Yeti', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TheRedYeti
include('fontawesome-6/Brands/TheRedYeti')

' renders the element
TheRedYeti('TheRedYeti', 'The Red Yeti', 'an optional tech label', 'an optional description')
@enduml
```

