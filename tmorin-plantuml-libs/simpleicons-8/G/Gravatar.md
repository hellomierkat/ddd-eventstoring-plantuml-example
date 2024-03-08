# Gravatar


```text
simpleicons-8/G/Gravatar
```

```text
include('simpleicons-8/G/Gravatar')
```



| Illustration | Gravatar |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gravatar.png) | ![illustration for Gravatar](../../simpleicons-8/G/Gravatar.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GravatarXs>`
- `<$GravatarSm>`
- `<$GravatarMd>`
- `<$GravatarLg>`





## Gravatar

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gravatar
include('simpleicons-8/G/Gravatar')

' renders the element
Gravatar('Gravatar', 'Gravatar', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gravatar
include('simpleicons-8/G/Gravatar')

' renders the element
Gravatar('Gravatar', 'Gravatar', 'an optional tech label', 'an optional description')
@enduml
```

