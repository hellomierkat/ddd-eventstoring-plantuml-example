# Clyp


```text
simpleicons-8/C/Clyp
```

```text
include('simpleicons-8/C/Clyp')
```



| Illustration | Clyp |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Clyp.png) | ![illustration for Clyp](../../simpleicons-8/C/Clyp.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ClypXs>`
- `<$ClypSm>`
- `<$ClypMd>`
- `<$ClypLg>`





## Clyp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Clyp
include('simpleicons-8/C/Clyp')

' renders the element
Clyp('Clyp', 'Clyp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Clyp
include('simpleicons-8/C/Clyp')

' renders the element
Clyp('Clyp', 'Clyp', 'an optional tech label', 'an optional description')
@enduml
```

