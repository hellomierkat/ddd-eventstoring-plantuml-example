# Torproject


```text
simpleicons-8/T/Torproject
```

```text
include('simpleicons-8/T/Torproject')
```



| Illustration | Torproject |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Torproject.png) | ![illustration for Torproject](../../simpleicons-8/T/Torproject.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TorprojectXs>`
- `<$TorprojectSm>`
- `<$TorprojectMd>`
- `<$TorprojectLg>`





## Torproject

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Torproject
include('simpleicons-8/T/Torproject')

' renders the element
Torproject('Torproject', 'Torproject', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Torproject
include('simpleicons-8/T/Torproject')

' renders the element
Torproject('Torproject', 'Torproject', 'an optional tech label', 'an optional description')
@enduml
```

