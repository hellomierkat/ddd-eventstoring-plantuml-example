# Trophy


```text
fontawesome-6/Solid/Trophy
```

```text
include('fontawesome-6/Solid/Trophy')
```



| Illustration | Trophy |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Trophy.png) | ![illustration for Trophy](../../fontawesome-6/Solid/Trophy.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TrophyXs>`
- `<$TrophySm>`
- `<$TrophyMd>`
- `<$TrophyLg>`





## Trophy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Trophy
include('fontawesome-6/Solid/Trophy')

' renders the element
Trophy('Trophy', 'Trophy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Trophy
include('fontawesome-6/Solid/Trophy')

' renders the element
Trophy('Trophy', 'Trophy', 'an optional tech label', 'an optional description')
@enduml
```

