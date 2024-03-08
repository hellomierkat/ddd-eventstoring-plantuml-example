# Mountain


```text
fontawesome-6/Solid/Mountain
```

```text
include('fontawesome-6/Solid/Mountain')
```



| Illustration | Mountain |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Mountain.png) | ![illustration for Mountain](../../fontawesome-6/Solid/Mountain.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MountainXs>`
- `<$MountainSm>`
- `<$MountainMd>`
- `<$MountainLg>`





## Mountain

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Mountain
include('fontawesome-6/Solid/Mountain')

' renders the element
Mountain('Mountain', 'Mountain', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mountain
include('fontawesome-6/Solid/Mountain')

' renders the element
Mountain('Mountain', 'Mountain', 'an optional tech label', 'an optional description')
@enduml
```

