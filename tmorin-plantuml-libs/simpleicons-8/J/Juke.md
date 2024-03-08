# Juke


```text
simpleicons-8/J/Juke
```

```text
include('simpleicons-8/J/Juke')
```



| Illustration | Juke |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/J/Juke.png) | ![illustration for Juke](../../simpleicons-8/J/Juke.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JukeXs>`
- `<$JukeSm>`
- `<$JukeMd>`
- `<$JukeLg>`





## Juke

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Juke
include('simpleicons-8/J/Juke')

' renders the element
Juke('Juke', 'Juke', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Juke
include('simpleicons-8/J/Juke')

' renders the element
Juke('Juke', 'Juke', 'an optional tech label', 'an optional description')
@enduml
```

