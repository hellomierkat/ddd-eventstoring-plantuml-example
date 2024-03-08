# Telegraph


```text
simpleicons-8/T/Telegraph
```

```text
include('simpleicons-8/T/Telegraph')
```



| Illustration | Telegraph |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Telegraph.png) | ![illustration for Telegraph](../../simpleicons-8/T/Telegraph.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TelegraphXs>`
- `<$TelegraphSm>`
- `<$TelegraphMd>`
- `<$TelegraphLg>`





## Telegraph

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Telegraph
include('simpleicons-8/T/Telegraph')

' renders the element
Telegraph('Telegraph', 'Telegraph', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Telegraph
include('simpleicons-8/T/Telegraph')

' renders the element
Telegraph('Telegraph', 'Telegraph', 'an optional tech label', 'an optional description')
@enduml
```

