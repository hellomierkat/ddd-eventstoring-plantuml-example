# Framework7


```text
simpleicons-8/F/Framework7
```

```text
include('simpleicons-8/F/Framework7')
```



| Illustration | Framework7 |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Framework7.png) | ![illustration for Framework7](../../simpleicons-8/F/Framework7.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Framework7Xs>`
- `<$Framework7Sm>`
- `<$Framework7Md>`
- `<$Framework7Lg>`





## Framework7

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Framework7
include('simpleicons-8/F/Framework7')

' renders the element
Framework7('Framework7', 'Framework7', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Framework7
include('simpleicons-8/F/Framework7')

' renders the element
Framework7('Framework7', 'Framework7', 'an optional tech label', 'an optional description')
@enduml
```

