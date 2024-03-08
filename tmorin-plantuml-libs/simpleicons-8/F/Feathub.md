# Feathub


```text
simpleicons-8/F/Feathub
```

```text
include('simpleicons-8/F/Feathub')
```



| Illustration | Feathub |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Feathub.png) | ![illustration for Feathub](../../simpleicons-8/F/Feathub.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FeathubXs>`
- `<$FeathubSm>`
- `<$FeathubMd>`
- `<$FeathubLg>`





## Feathub

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Feathub
include('simpleicons-8/F/Feathub')

' renders the element
Feathub('Feathub', 'Feathub', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Feathub
include('simpleicons-8/F/Feathub')

' renders the element
Feathub('Feathub', 'Feathub', 'an optional tech label', 'an optional description')
@enduml
```

