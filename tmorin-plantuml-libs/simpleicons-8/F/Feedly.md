# Feedly


```text
simpleicons-8/F/Feedly
```

```text
include('simpleicons-8/F/Feedly')
```



| Illustration | Feedly |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Feedly.png) | ![illustration for Feedly](../../simpleicons-8/F/Feedly.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FeedlyXs>`
- `<$FeedlySm>`
- `<$FeedlyMd>`
- `<$FeedlyLg>`





## Feedly

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Feedly
include('simpleicons-8/F/Feedly')

' renders the element
Feedly('Feedly', 'Feedly', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Feedly
include('simpleicons-8/F/Feedly')

' renders the element
Feedly('Feedly', 'Feedly', 'an optional tech label', 'an optional description')
@enduml
```

