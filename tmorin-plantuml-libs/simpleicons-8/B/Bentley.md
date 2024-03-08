# Bentley


```text
simpleicons-8/B/Bentley
```

```text
include('simpleicons-8/B/Bentley')
```



| Illustration | Bentley |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Bentley.png) | ![illustration for Bentley](../../simpleicons-8/B/Bentley.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BentleyXs>`
- `<$BentleySm>`
- `<$BentleyMd>`
- `<$BentleyLg>`





## Bentley

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Bentley
include('simpleicons-8/B/Bentley')

' renders the element
Bentley('Bentley', 'Bentley', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bentley
include('simpleicons-8/B/Bentley')

' renders the element
Bentley('Bentley', 'Bentley', 'an optional tech label', 'an optional description')
@enduml
```

