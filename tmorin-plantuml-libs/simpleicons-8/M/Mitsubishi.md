# Mitsubishi


```text
simpleicons-8/M/Mitsubishi
```

```text
include('simpleicons-8/M/Mitsubishi')
```



| Illustration | Mitsubishi |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Mitsubishi.png) | ![illustration for Mitsubishi](../../simpleicons-8/M/Mitsubishi.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MitsubishiXs>`
- `<$MitsubishiSm>`
- `<$MitsubishiMd>`
- `<$MitsubishiLg>`





## Mitsubishi

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Mitsubishi
include('simpleicons-8/M/Mitsubishi')

' renders the element
Mitsubishi('Mitsubishi', 'Mitsubishi', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mitsubishi
include('simpleicons-8/M/Mitsubishi')

' renders the element
Mitsubishi('Mitsubishi', 'Mitsubishi', 'an optional tech label', 'an optional description')
@enduml
```

