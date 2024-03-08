# Livejournal


```text
simpleicons-8/L/Livejournal
```

```text
include('simpleicons-8/L/Livejournal')
```



| Illustration | Livejournal |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Livejournal.png) | ![illustration for Livejournal](../../simpleicons-8/L/Livejournal.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LivejournalXs>`
- `<$LivejournalSm>`
- `<$LivejournalMd>`
- `<$LivejournalLg>`





## Livejournal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Livejournal
include('simpleicons-8/L/Livejournal')

' renders the element
Livejournal('Livejournal', 'Livejournal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Livejournal
include('simpleicons-8/L/Livejournal')

' renders the element
Livejournal('Livejournal', 'Livejournal', 'an optional tech label', 'an optional description')
@enduml
```

