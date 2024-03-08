# Ray


```text
simpleicons-8/R/Ray
```

```text
include('simpleicons-8/R/Ray')
```



| Illustration | Ray |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Ray.png) | ![illustration for Ray](../../simpleicons-8/R/Ray.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RayXs>`
- `<$RaySm>`
- `<$RayMd>`
- `<$RayLg>`





## Ray

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ray
include('simpleicons-8/R/Ray')

' renders the element
Ray('Ray', 'Ray', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ray
include('simpleicons-8/R/Ray')

' renders the element
Ray('Ray', 'Ray', 'an optional tech label', 'an optional description')
@enduml
```

