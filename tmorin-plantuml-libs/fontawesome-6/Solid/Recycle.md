# Recycle


```text
fontawesome-6/Solid/Recycle
```

```text
include('fontawesome-6/Solid/Recycle')
```



| Illustration | Recycle |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Recycle.png) | ![illustration for Recycle](../../fontawesome-6/Solid/Recycle.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RecycleXs>`
- `<$RecycleSm>`
- `<$RecycleMd>`
- `<$RecycleLg>`





## Recycle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Recycle
include('fontawesome-6/Solid/Recycle')

' renders the element
Recycle('Recycle', 'Recycle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Recycle
include('fontawesome-6/Solid/Recycle')

' renders the element
Recycle('Recycle', 'Recycle', 'an optional tech label', 'an optional description')
@enduml
```

