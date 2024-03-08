# Toshiba


```text
simpleicons-8/T/Toshiba
```

```text
include('simpleicons-8/T/Toshiba')
```



| Illustration | Toshiba |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Toshiba.png) | ![illustration for Toshiba](../../simpleicons-8/T/Toshiba.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ToshibaXs>`
- `<$ToshibaSm>`
- `<$ToshibaMd>`
- `<$ToshibaLg>`





## Toshiba

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Toshiba
include('simpleicons-8/T/Toshiba')

' renders the element
Toshiba('Toshiba', 'Toshiba', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Toshiba
include('simpleicons-8/T/Toshiba')

' renders the element
Toshiba('Toshiba', 'Toshiba', 'an optional tech label', 'an optional description')
@enduml
```

