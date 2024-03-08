# Gnome


```text
simpleicons-8/G/Gnome
```

```text
include('simpleicons-8/G/Gnome')
```



| Illustration | Gnome |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gnome.png) | ![illustration for Gnome](../../simpleicons-8/G/Gnome.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GnomeXs>`
- `<$GnomeSm>`
- `<$GnomeMd>`
- `<$GnomeLg>`





## Gnome

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gnome
include('simpleicons-8/G/Gnome')

' renders the element
Gnome('Gnome', 'Gnome', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gnome
include('simpleicons-8/G/Gnome')

' renders the element
Gnome('Gnome', 'Gnome', 'an optional tech label', 'an optional description')
@enduml
```

