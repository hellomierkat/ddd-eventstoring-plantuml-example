# Sololearn


```text
simpleicons-8/S/Sololearn
```

```text
include('simpleicons-8/S/Sololearn')
```



| Illustration | Sololearn |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Sololearn.png) | ![illustration for Sololearn](../../simpleicons-8/S/Sololearn.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SololearnXs>`
- `<$SololearnSm>`
- `<$SololearnMd>`
- `<$SololearnLg>`





## Sololearn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Sololearn
include('simpleicons-8/S/Sololearn')

' renders the element
Sololearn('Sololearn', 'Sololearn', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sololearn
include('simpleicons-8/S/Sololearn')

' renders the element
Sololearn('Sololearn', 'Sololearn', 'an optional tech label', 'an optional description')
@enduml
```

