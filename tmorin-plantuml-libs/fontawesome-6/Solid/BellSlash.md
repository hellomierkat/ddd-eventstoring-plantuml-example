# BellSlash


```text
fontawesome-6/Solid/BellSlash
```

```text
include('fontawesome-6/Solid/BellSlash')
```



| Illustration | BellSlash |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BellSlash.png) | ![illustration for BellSlash](../../fontawesome-6/Solid/BellSlash.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BellSlashXs>`
- `<$BellSlashSm>`
- `<$BellSlashMd>`
- `<$BellSlashLg>`





## BellSlash

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BellSlash
include('fontawesome-6/Solid/BellSlash')

' renders the element
BellSlash('BellSlash', 'Bell Slash', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BellSlash
include('fontawesome-6/Solid/BellSlash')

' renders the element
BellSlash('BellSlash', 'Bell Slash', 'an optional tech label', 'an optional description')
@enduml
```

