# KeyboardCapslock


```text
material-4/Hardware/KeyboardCapslock
```

```text
include('material-4/Hardware/KeyboardCapslock')
```



| Illustration | KeyboardCapslock |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Hardware/KeyboardCapslock.png) | ![illustration for KeyboardCapslock](../../material-4/Hardware/KeyboardCapslock.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KeyboardCapslockXs>`
- `<$KeyboardCapslockSm>`
- `<$KeyboardCapslockMd>`
- `<$KeyboardCapslockLg>`





## KeyboardCapslock

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element KeyboardCapslock
include('material-4/Hardware/KeyboardCapslock')

' renders the element
KeyboardCapslock('KeyboardCapslock', 'Keyboard Capslock', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element KeyboardCapslock
include('material-4/Hardware/KeyboardCapslock')

' renders the element
KeyboardCapslock('KeyboardCapslock', 'Keyboard Capslock', 'an optional tech label', 'an optional description')
@enduml
```

