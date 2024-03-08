# Minds


```text
simpleicons-8/M/Minds
```

```text
include('simpleicons-8/M/Minds')
```



| Illustration | Minds |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Minds.png) | ![illustration for Minds](../../simpleicons-8/M/Minds.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MindsXs>`
- `<$MindsSm>`
- `<$MindsMd>`
- `<$MindsLg>`





## Minds

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Minds
include('simpleicons-8/M/Minds')

' renders the element
Minds('Minds', 'Minds', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Minds
include('simpleicons-8/M/Minds')

' renders the element
Minds('Minds', 'Minds', 'an optional tech label', 'an optional description')
@enduml
```

