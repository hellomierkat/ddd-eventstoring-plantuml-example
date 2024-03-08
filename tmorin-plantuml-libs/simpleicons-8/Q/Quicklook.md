# Quicklook


```text
simpleicons-8/Q/Quicklook
```

```text
include('simpleicons-8/Q/Quicklook')
```



| Illustration | Quicklook |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/Q/Quicklook.png) | ![illustration for Quicklook](../../simpleicons-8/Q/Quicklook.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$QuicklookXs>`
- `<$QuicklookSm>`
- `<$QuicklookMd>`
- `<$QuicklookLg>`





## Quicklook

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Quicklook
include('simpleicons-8/Q/Quicklook')

' renders the element
Quicklook('Quicklook', 'Quicklook', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Quicklook
include('simpleicons-8/Q/Quicklook')

' renders the element
Quicklook('Quicklook', 'Quicklook', 'an optional tech label', 'an optional description')
@enduml
```

