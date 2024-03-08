# FormatAlignRight


```text
material-4/Editor/FormatAlignRight
```

```text
include('material-4/Editor/FormatAlignRight')
```



| Illustration | FormatAlignRight |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/FormatAlignRight.png) | ![illustration for FormatAlignRight](../../material-4/Editor/FormatAlignRight.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FormatAlignRightXs>`
- `<$FormatAlignRightSm>`
- `<$FormatAlignRightMd>`
- `<$FormatAlignRightLg>`





## FormatAlignRight

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FormatAlignRight
include('material-4/Editor/FormatAlignRight')

' renders the element
FormatAlignRight('FormatAlignRight', 'Format Align Right', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FormatAlignRight
include('material-4/Editor/FormatAlignRight')

' renders the element
FormatAlignRight('FormatAlignRight', 'Format Align Right', 'an optional tech label', 'an optional description')
@enduml
```

