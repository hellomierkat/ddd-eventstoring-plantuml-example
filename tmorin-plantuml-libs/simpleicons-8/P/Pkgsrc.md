# Pkgsrc


```text
simpleicons-8/P/Pkgsrc
```

```text
include('simpleicons-8/P/Pkgsrc')
```



| Illustration | Pkgsrc |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Pkgsrc.png) | ![illustration for Pkgsrc](../../simpleicons-8/P/Pkgsrc.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PkgsrcXs>`
- `<$PkgsrcSm>`
- `<$PkgsrcMd>`
- `<$PkgsrcLg>`





## Pkgsrc

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Pkgsrc
include('simpleicons-8/P/Pkgsrc')

' renders the element
Pkgsrc('Pkgsrc', 'Pkgsrc', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pkgsrc
include('simpleicons-8/P/Pkgsrc')

' renders the element
Pkgsrc('Pkgsrc', 'Pkgsrc', 'an optional tech label', 'an optional description')
@enduml
```

