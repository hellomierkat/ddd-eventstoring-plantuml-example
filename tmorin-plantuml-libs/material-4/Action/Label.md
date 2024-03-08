# Label


```text
material-4/Action/Label
```

```text
include('material-4/Action/Label')
```



| Illustration | Label |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Label.png) | ![illustration for Label](../../material-4/Action/Label.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LabelXs>`
- `<$LabelSm>`
- `<$LabelMd>`
- `<$LabelLg>`





## Label

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Label
include('material-4/Action/Label')

' renders the element
Label('Label', 'Label', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Label
include('material-4/Action/Label')

' renders the element
Label('Label', 'Label', 'an optional tech label', 'an optional description')
@enduml
```

