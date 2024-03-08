# Undo


```text
material-4/Content/Undo
```

```text
include('material-4/Content/Undo')
```



| Illustration | Undo |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Undo.png) | ![illustration for Undo](../../material-4/Content/Undo.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$UndoXs>`
- `<$UndoSm>`
- `<$UndoMd>`
- `<$UndoLg>`





## Undo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Undo
include('material-4/Content/Undo')

' renders the element
Undo('Undo', 'Undo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Undo
include('material-4/Content/Undo')

' renders the element
Undo('Undo', 'Undo', 'an optional tech label', 'an optional description')
@enduml
```

