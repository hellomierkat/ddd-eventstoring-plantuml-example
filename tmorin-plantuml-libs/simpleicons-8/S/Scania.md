# Scania


```text
simpleicons-8/S/Scania
```

```text
include('simpleicons-8/S/Scania')
```



| Illustration | Scania |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Scania.png) | ![illustration for Scania](../../simpleicons-8/S/Scania.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ScaniaXs>`
- `<$ScaniaSm>`
- `<$ScaniaMd>`
- `<$ScaniaLg>`





## Scania

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Scania
include('simpleicons-8/S/Scania')

' renders the element
Scania('Scania', 'Scania', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Scania
include('simpleicons-8/S/Scania')

' renders the element
Scania('Scania', 'Scania', 'an optional tech label', 'an optional description')
@enduml
```

