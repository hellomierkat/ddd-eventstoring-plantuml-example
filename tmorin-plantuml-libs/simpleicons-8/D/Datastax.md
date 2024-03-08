# Datastax


```text
simpleicons-8/D/Datastax
```

```text
include('simpleicons-8/D/Datastax')
```



| Illustration | Datastax |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/D/Datastax.png) | ![illustration for Datastax](../../simpleicons-8/D/Datastax.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DatastaxXs>`
- `<$DatastaxSm>`
- `<$DatastaxMd>`
- `<$DatastaxLg>`





## Datastax

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Datastax
include('simpleicons-8/D/Datastax')

' renders the element
Datastax('Datastax', 'Datastax', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Datastax
include('simpleicons-8/D/Datastax')

' renders the element
Datastax('Datastax', 'Datastax', 'an optional tech label', 'an optional description')
@enduml
```

