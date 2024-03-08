# Icq


```text
simpleicons-8/I/Icq
```

```text
include('simpleicons-8/I/Icq')
```



| Illustration | Icq |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Icq.png) | ![illustration for Icq](../../simpleicons-8/I/Icq.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IcqXs>`
- `<$IcqSm>`
- `<$IcqMd>`
- `<$IcqLg>`





## Icq

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Icq
include('simpleicons-8/I/Icq')

' renders the element
Icq('Icq', 'Icq', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Icq
include('simpleicons-8/I/Icq')

' renders the element
Icq('Icq', 'Icq', 'an optional tech label', 'an optional description')
@enduml
```

