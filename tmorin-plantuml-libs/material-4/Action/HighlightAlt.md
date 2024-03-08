# HighlightAlt


```text
material-4/Action/HighlightAlt
```

```text
include('material-4/Action/HighlightAlt')
```



| Illustration | HighlightAlt |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/HighlightAlt.png) | ![illustration for HighlightAlt](../../material-4/Action/HighlightAlt.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HighlightAltXs>`
- `<$HighlightAltSm>`
- `<$HighlightAltMd>`
- `<$HighlightAltLg>`





## HighlightAlt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element HighlightAlt
include('material-4/Action/HighlightAlt')

' renders the element
HighlightAlt('HighlightAlt', 'Highlight Alt', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HighlightAlt
include('material-4/Action/HighlightAlt')

' renders the element
HighlightAlt('HighlightAlt', 'Highlight Alt', 'an optional tech label', 'an optional description')
@enduml
```

