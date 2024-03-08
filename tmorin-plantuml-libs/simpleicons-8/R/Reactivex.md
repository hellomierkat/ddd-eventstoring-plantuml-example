# Reactivex


```text
simpleicons-8/R/Reactivex
```

```text
include('simpleicons-8/R/Reactivex')
```



| Illustration | Reactivex |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Reactivex.png) | ![illustration for Reactivex](../../simpleicons-8/R/Reactivex.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReactivexXs>`
- `<$ReactivexSm>`
- `<$ReactivexMd>`
- `<$ReactivexLg>`





## Reactivex

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Reactivex
include('simpleicons-8/R/Reactivex')

' renders the element
Reactivex('Reactivex', 'Reactivex', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reactivex
include('simpleicons-8/R/Reactivex')

' renders the element
Reactivex('Reactivex', 'Reactivex', 'an optional tech label', 'an optional description')
@enduml
```

