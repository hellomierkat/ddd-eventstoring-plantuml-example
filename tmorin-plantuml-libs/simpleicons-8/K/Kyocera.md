# Kyocera


```text
simpleicons-8/K/Kyocera
```

```text
include('simpleicons-8/K/Kyocera')
```



| Illustration | Kyocera |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/K/Kyocera.png) | ![illustration for Kyocera](../../simpleicons-8/K/Kyocera.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KyoceraXs>`
- `<$KyoceraSm>`
- `<$KyoceraMd>`
- `<$KyoceraLg>`





## Kyocera

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Kyocera
include('simpleicons-8/K/Kyocera')

' renders the element
Kyocera('Kyocera', 'Kyocera', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Kyocera
include('simpleicons-8/K/Kyocera')

' renders the element
Kyocera('Kyocera', 'Kyocera', 'an optional tech label', 'an optional description')
@enduml
```

