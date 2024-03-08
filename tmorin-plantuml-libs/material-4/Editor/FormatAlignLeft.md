# FormatAlignLeft


```text
material-4/Editor/FormatAlignLeft
```

```text
include('material-4/Editor/FormatAlignLeft')
```



| Illustration | FormatAlignLeft |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/FormatAlignLeft.png) | ![illustration for FormatAlignLeft](../../material-4/Editor/FormatAlignLeft.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FormatAlignLeftXs>`
- `<$FormatAlignLeftSm>`
- `<$FormatAlignLeftMd>`
- `<$FormatAlignLeftLg>`





## FormatAlignLeft

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FormatAlignLeft
include('material-4/Editor/FormatAlignLeft')

' renders the element
FormatAlignLeft('FormatAlignLeft', 'Format Align Left', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FormatAlignLeft
include('material-4/Editor/FormatAlignLeft')

' renders the element
FormatAlignLeft('FormatAlignLeft', 'Format Align Left', 'an optional tech label', 'an optional description')
@enduml
```

