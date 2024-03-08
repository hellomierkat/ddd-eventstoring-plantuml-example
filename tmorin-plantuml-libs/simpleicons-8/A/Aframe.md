# Aframe


```text
simpleicons-8/A/Aframe
```

```text
include('simpleicons-8/A/Aframe')
```



| Illustration | Aframe |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Aframe.png) | ![illustration for Aframe](../../simpleicons-8/A/Aframe.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AframeXs>`
- `<$AframeSm>`
- `<$AframeMd>`
- `<$AframeLg>`





## Aframe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Aframe
include('simpleicons-8/A/Aframe')

' renders the element
Aframe('Aframe', 'Aframe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Aframe
include('simpleicons-8/A/Aframe')

' renders the element
Aframe('Aframe', 'Aframe', 'an optional tech label', 'an optional description')
@enduml
```

