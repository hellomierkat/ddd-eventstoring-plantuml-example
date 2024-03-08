# Tablecheck


```text
simpleicons-8/T/Tablecheck
```

```text
include('simpleicons-8/T/Tablecheck')
```



| Illustration | Tablecheck |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Tablecheck.png) | ![illustration for Tablecheck](../../simpleicons-8/T/Tablecheck.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TablecheckXs>`
- `<$TablecheckSm>`
- `<$TablecheckMd>`
- `<$TablecheckLg>`





## Tablecheck

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Tablecheck
include('simpleicons-8/T/Tablecheck')

' renders the element
Tablecheck('Tablecheck', 'Tablecheck', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Tablecheck
include('simpleicons-8/T/Tablecheck')

' renders the element
Tablecheck('Tablecheck', 'Tablecheck', 'an optional tech label', 'an optional description')
@enduml
```

