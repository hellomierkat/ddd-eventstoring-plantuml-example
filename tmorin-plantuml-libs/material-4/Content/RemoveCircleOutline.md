# RemoveCircleOutline


```text
material-4/Content/RemoveCircleOutline
```

```text
include('material-4/Content/RemoveCircleOutline')
```



| Illustration | RemoveCircleOutline |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/RemoveCircleOutline.png) | ![illustration for RemoveCircleOutline](../../material-4/Content/RemoveCircleOutline.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RemoveCircleOutlineXs>`
- `<$RemoveCircleOutlineSm>`
- `<$RemoveCircleOutlineMd>`
- `<$RemoveCircleOutlineLg>`





## RemoveCircleOutline

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element RemoveCircleOutline
include('material-4/Content/RemoveCircleOutline')

' renders the element
RemoveCircleOutline('RemoveCircleOutline', 'Remove Circle Outline', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element RemoveCircleOutline
include('material-4/Content/RemoveCircleOutline')

' renders the element
RemoveCircleOutline('RemoveCircleOutline', 'Remove Circle Outline', 'an optional tech label', 'an optional description')
@enduml
```

