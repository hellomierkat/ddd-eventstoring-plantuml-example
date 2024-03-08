# FormatTextdirectionRToL


```text
material-4/Editor/FormatTextdirectionRToL
```

```text
include('material-4/Editor/FormatTextdirectionRToL')
```



| Illustration | FormatTextdirectionRToL |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/FormatTextdirectionRToL.png) | ![illustration for FormatTextdirectionRToL](../../material-4/Editor/FormatTextdirectionRToL.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FormatTextdirectionRToLXs>`
- `<$FormatTextdirectionRToLSm>`
- `<$FormatTextdirectionRToLMd>`
- `<$FormatTextdirectionRToLLg>`





## FormatTextdirectionRToL

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FormatTextdirectionRToL
include('material-4/Editor/FormatTextdirectionRToL')

' renders the element
FormatTextdirectionRToL('FormatTextdirectionRToL', 'Format Textdirection R To L', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FormatTextdirectionRToL
include('material-4/Editor/FormatTextdirectionRToL')

' renders the element
FormatTextdirectionRToL('FormatTextdirectionRToL', 'Format Textdirection R To L', 'an optional tech label', 'an optional description')
@enduml
```

