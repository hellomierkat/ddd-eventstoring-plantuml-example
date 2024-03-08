# Jameson


```text
simpleicons-8/J/Jameson
```

```text
include('simpleicons-8/J/Jameson')
```



| Illustration | Jameson |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/J/Jameson.png) | ![illustration for Jameson](../../simpleicons-8/J/Jameson.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JamesonXs>`
- `<$JamesonSm>`
- `<$JamesonMd>`
- `<$JamesonLg>`





## Jameson

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Jameson
include('simpleicons-8/J/Jameson')

' renders the element
Jameson('Jameson', 'Jameson', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jameson
include('simpleicons-8/J/Jameson')

' renders the element
Jameson('Jameson', 'Jameson', 'an optional tech label', 'an optional description')
@enduml
```

