# FontAwesome


```text
fontawesome-6/Solid/FontAwesome
```

```text
include('fontawesome-6/Solid/FontAwesome')
```



| Illustration | FontAwesome |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FontAwesome.png) | ![illustration for FontAwesome](../../fontawesome-6/Solid/FontAwesome.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FontAwesomeXs>`
- `<$FontAwesomeSm>`
- `<$FontAwesomeMd>`
- `<$FontAwesomeLg>`





## FontAwesome

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FontAwesome
include('fontawesome-6/Solid/FontAwesome')

' renders the element
FontAwesome('FontAwesome', 'Font Awesome', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FontAwesome
include('fontawesome-6/Solid/FontAwesome')

' renders the element
FontAwesome('FontAwesome', 'Font Awesome', 'an optional tech label', 'an optional description')
@enduml
```

