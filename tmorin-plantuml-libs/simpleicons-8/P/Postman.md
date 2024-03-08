# Postman


```text
simpleicons-8/P/Postman
```

```text
include('simpleicons-8/P/Postman')
```



| Illustration | Postman |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Postman.png) | ![illustration for Postman](../../simpleicons-8/P/Postman.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PostmanXs>`
- `<$PostmanSm>`
- `<$PostmanMd>`
- `<$PostmanLg>`





## Postman

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Postman
include('simpleicons-8/P/Postman')

' renders the element
Postman('Postman', 'Postman', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Postman
include('simpleicons-8/P/Postman')

' renders the element
Postman('Postman', 'Postman', 'an optional tech label', 'an optional description')
@enduml
```

