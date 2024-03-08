# Tga


```text
simpleicons-8/T/Tga
```

```text
include('simpleicons-8/T/Tga')
```



| Illustration | Tga |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Tga.png) | ![illustration for Tga](../../simpleicons-8/T/Tga.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TgaXs>`
- `<$TgaSm>`
- `<$TgaMd>`
- `<$TgaLg>`





## Tga

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Tga
include('simpleicons-8/T/Tga')

' renders the element
Tga('Tga', 'Tga', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Tga
include('simpleicons-8/T/Tga')

' renders the element
Tga('Tga', 'Tga', 'an optional tech label', 'an optional description')
@enduml
```

