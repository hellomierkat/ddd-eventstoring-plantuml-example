# Prettier


```text
simpleicons-8/P/Prettier
```

```text
include('simpleicons-8/P/Prettier')
```



| Illustration | Prettier |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Prettier.png) | ![illustration for Prettier](../../simpleicons-8/P/Prettier.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PrettierXs>`
- `<$PrettierSm>`
- `<$PrettierMd>`
- `<$PrettierLg>`





## Prettier

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Prettier
include('simpleicons-8/P/Prettier')

' renders the element
Prettier('Prettier', 'Prettier', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Prettier
include('simpleicons-8/P/Prettier')

' renders the element
Prettier('Prettier', 'Prettier', 'an optional tech label', 'an optional description')
@enduml
```

