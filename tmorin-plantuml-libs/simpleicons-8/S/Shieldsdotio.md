# Shieldsdotio


```text
simpleicons-8/S/Shieldsdotio
```

```text
include('simpleicons-8/S/Shieldsdotio')
```



| Illustration | Shieldsdotio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Shieldsdotio.png) | ![illustration for Shieldsdotio](../../simpleicons-8/S/Shieldsdotio.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ShieldsdotioXs>`
- `<$ShieldsdotioSm>`
- `<$ShieldsdotioMd>`
- `<$ShieldsdotioLg>`





## Shieldsdotio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Shieldsdotio
include('simpleicons-8/S/Shieldsdotio')

' renders the element
Shieldsdotio('Shieldsdotio', 'Shieldsdotio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Shieldsdotio
include('simpleicons-8/S/Shieldsdotio')

' renders the element
Shieldsdotio('Shieldsdotio', 'Shieldsdotio', 'an optional tech label', 'an optional description')
@enduml
```

