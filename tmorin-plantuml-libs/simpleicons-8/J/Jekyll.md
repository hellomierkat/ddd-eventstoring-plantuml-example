# Jekyll


```text
simpleicons-8/J/Jekyll
```

```text
include('simpleicons-8/J/Jekyll')
```



| Illustration | Jekyll |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/J/Jekyll.png) | ![illustration for Jekyll](../../simpleicons-8/J/Jekyll.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JekyllXs>`
- `<$JekyllSm>`
- `<$JekyllMd>`
- `<$JekyllLg>`





## Jekyll

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Jekyll
include('simpleicons-8/J/Jekyll')

' renders the element
Jekyll('Jekyll', 'Jekyll', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jekyll
include('simpleicons-8/J/Jekyll')

' renders the element
Jekyll('Jekyll', 'Jekyll', 'an optional tech label', 'an optional description')
@enduml
```

