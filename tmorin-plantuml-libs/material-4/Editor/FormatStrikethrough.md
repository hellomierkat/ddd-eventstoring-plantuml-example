# FormatStrikethrough


```text
material-4/Editor/FormatStrikethrough
```

```text
include('material-4/Editor/FormatStrikethrough')
```



| Illustration | FormatStrikethrough |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/FormatStrikethrough.png) | ![illustration for FormatStrikethrough](../../material-4/Editor/FormatStrikethrough.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FormatStrikethroughXs>`
- `<$FormatStrikethroughSm>`
- `<$FormatStrikethroughMd>`
- `<$FormatStrikethroughLg>`





## FormatStrikethrough

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FormatStrikethrough
include('material-4/Editor/FormatStrikethrough')

' renders the element
FormatStrikethrough('FormatStrikethrough', 'Format Strikethrough', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FormatStrikethrough
include('material-4/Editor/FormatStrikethrough')

' renders the element
FormatStrikethrough('FormatStrikethrough', 'Format Strikethrough', 'an optional tech label', 'an optional description')
@enduml
```

