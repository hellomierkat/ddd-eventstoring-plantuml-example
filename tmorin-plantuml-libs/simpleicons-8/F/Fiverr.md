# Fiverr


```text
simpleicons-8/F/Fiverr
```

```text
include('simpleicons-8/F/Fiverr')
```



| Illustration | Fiverr |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Fiverr.png) | ![illustration for Fiverr](../../simpleicons-8/F/Fiverr.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FiverrXs>`
- `<$FiverrSm>`
- `<$FiverrMd>`
- `<$FiverrLg>`





## Fiverr

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Fiverr
include('simpleicons-8/F/Fiverr')

' renders the element
Fiverr('Fiverr', 'Fiverr', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fiverr
include('simpleicons-8/F/Fiverr')

' renders the element
Fiverr('Fiverr', 'Fiverr', 'an optional tech label', 'an optional description')
@enduml
```

