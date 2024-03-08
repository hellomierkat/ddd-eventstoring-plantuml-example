# Tty


```text
fontawesome-6/Solid/Tty
```

```text
include('fontawesome-6/Solid/Tty')
```



| Illustration | Tty |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Tty.png) | ![illustration for Tty](../../fontawesome-6/Solid/Tty.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TtyXs>`
- `<$TtySm>`
- `<$TtyMd>`
- `<$TtyLg>`





## Tty

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Tty
include('fontawesome-6/Solid/Tty')

' renders the element
Tty('Tty', 'Tty', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Tty
include('fontawesome-6/Solid/Tty')

' renders the element
Tty('Tty', 'Tty', 'an optional tech label', 'an optional description')
@enduml
```

