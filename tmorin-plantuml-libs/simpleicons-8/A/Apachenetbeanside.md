# Apachenetbeanside


```text
simpleicons-8/A/Apachenetbeanside
```

```text
include('simpleicons-8/A/Apachenetbeanside')
```



| Illustration | Apachenetbeanside |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Apachenetbeanside.png) | ![illustration for Apachenetbeanside](../../simpleicons-8/A/Apachenetbeanside.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ApachenetbeansideXs>`
- `<$ApachenetbeansideSm>`
- `<$ApachenetbeansideMd>`
- `<$ApachenetbeansideLg>`





## Apachenetbeanside

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Apachenetbeanside
include('simpleicons-8/A/Apachenetbeanside')

' renders the element
Apachenetbeanside('Apachenetbeanside', 'Apachenetbeanside', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Apachenetbeanside
include('simpleicons-8/A/Apachenetbeanside')

' renders the element
Apachenetbeanside('Apachenetbeanside', 'Apachenetbeanside', 'an optional tech label', 'an optional description')
@enduml
```

