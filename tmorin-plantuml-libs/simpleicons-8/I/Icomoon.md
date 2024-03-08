# Icomoon


```text
simpleicons-8/I/Icomoon
```

```text
include('simpleicons-8/I/Icomoon')
```



| Illustration | Icomoon |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Icomoon.png) | ![illustration for Icomoon](../../simpleicons-8/I/Icomoon.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IcomoonXs>`
- `<$IcomoonSm>`
- `<$IcomoonMd>`
- `<$IcomoonLg>`





## Icomoon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Icomoon
include('simpleicons-8/I/Icomoon')

' renders the element
Icomoon('Icomoon', 'Icomoon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Icomoon
include('simpleicons-8/I/Icomoon')

' renders the element
Icomoon('Icomoon', 'Icomoon', 'an optional tech label', 'an optional description')
@enduml
```

