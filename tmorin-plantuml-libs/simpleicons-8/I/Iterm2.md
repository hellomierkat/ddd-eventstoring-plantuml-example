# Iterm2


```text
simpleicons-8/I/Iterm2
```

```text
include('simpleicons-8/I/Iterm2')
```



| Illustration | Iterm2 |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Iterm2.png) | ![illustration for Iterm2](../../simpleicons-8/I/Iterm2.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Iterm2Xs>`
- `<$Iterm2Sm>`
- `<$Iterm2Md>`
- `<$Iterm2Lg>`





## Iterm2

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Iterm2
include('simpleicons-8/I/Iterm2')

' renders the element
Iterm2('Iterm2', 'Iterm2', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Iterm2
include('simpleicons-8/I/Iterm2')

' renders the element
Iterm2('Iterm2', 'Iterm2', 'an optional tech label', 'an optional description')
@enduml
```

