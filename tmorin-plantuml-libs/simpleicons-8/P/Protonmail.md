# Protonmail


```text
simpleicons-8/P/Protonmail
```

```text
include('simpleicons-8/P/Protonmail')
```



| Illustration | Protonmail |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Protonmail.png) | ![illustration for Protonmail](../../simpleicons-8/P/Protonmail.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ProtonmailXs>`
- `<$ProtonmailSm>`
- `<$ProtonmailMd>`
- `<$ProtonmailLg>`





## Protonmail

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Protonmail
include('simpleicons-8/P/Protonmail')

' renders the element
Protonmail('Protonmail', 'Protonmail', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Protonmail
include('simpleicons-8/P/Protonmail')

' renders the element
Protonmail('Protonmail', 'Protonmail', 'an optional tech label', 'an optional description')
@enduml
```

