# Wpengine


```text
simpleicons-8/W/Wpengine
```

```text
include('simpleicons-8/W/Wpengine')
```



| Illustration | Wpengine |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/W/Wpengine.png) | ![illustration for Wpengine](../../simpleicons-8/W/Wpengine.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WpengineXs>`
- `<$WpengineSm>`
- `<$WpengineMd>`
- `<$WpengineLg>`





## Wpengine

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Wpengine
include('simpleicons-8/W/Wpengine')

' renders the element
Wpengine('Wpengine', 'Wpengine', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wpengine
include('simpleicons-8/W/Wpengine')

' renders the element
Wpengine('Wpengine', 'Wpengine', 'an optional tech label', 'an optional description')
@enduml
```

