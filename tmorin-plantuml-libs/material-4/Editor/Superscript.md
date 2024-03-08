# Superscript


```text
material-4/Editor/Superscript
```

```text
include('material-4/Editor/Superscript')
```



| Illustration | Superscript |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/Superscript.png) | ![illustration for Superscript](../../material-4/Editor/Superscript.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SuperscriptXs>`
- `<$SuperscriptSm>`
- `<$SuperscriptMd>`
- `<$SuperscriptLg>`





## Superscript

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Superscript
include('material-4/Editor/Superscript')

' renders the element
Superscript('Superscript', 'Superscript', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Superscript
include('material-4/Editor/Superscript')

' renders the element
Superscript('Superscript', 'Superscript', 'an optional tech label', 'an optional description')
@enduml
```

