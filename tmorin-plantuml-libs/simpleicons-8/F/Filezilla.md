# Filezilla


```text
simpleicons-8/F/Filezilla
```

```text
include('simpleicons-8/F/Filezilla')
```



| Illustration | Filezilla |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Filezilla.png) | ![illustration for Filezilla](../../simpleicons-8/F/Filezilla.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FilezillaXs>`
- `<$FilezillaSm>`
- `<$FilezillaMd>`
- `<$FilezillaLg>`





## Filezilla

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Filezilla
include('simpleicons-8/F/Filezilla')

' renders the element
Filezilla('Filezilla', 'Filezilla', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Filezilla
include('simpleicons-8/F/Filezilla')

' renders the element
Filezilla('Filezilla', 'Filezilla', 'an optional tech label', 'an optional description')
@enduml
```

