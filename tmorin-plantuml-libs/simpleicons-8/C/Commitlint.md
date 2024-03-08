# Commitlint


```text
simpleicons-8/C/Commitlint
```

```text
include('simpleicons-8/C/Commitlint')
```



| Illustration | Commitlint |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Commitlint.png) | ![illustration for Commitlint](../../simpleicons-8/C/Commitlint.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CommitlintXs>`
- `<$CommitlintSm>`
- `<$CommitlintMd>`
- `<$CommitlintLg>`





## Commitlint

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Commitlint
include('simpleicons-8/C/Commitlint')

' renders the element
Commitlint('Commitlint', 'Commitlint', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Commitlint
include('simpleicons-8/C/Commitlint')

' renders the element
Commitlint('Commitlint', 'Commitlint', 'an optional tech label', 'an optional description')
@enduml
```

