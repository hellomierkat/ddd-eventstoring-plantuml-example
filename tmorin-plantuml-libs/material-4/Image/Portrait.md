# Portrait


```text
material-4/Image/Portrait
```

```text
include('material-4/Image/Portrait')
```



| Illustration | Portrait |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Portrait.png) | ![illustration for Portrait](../../material-4/Image/Portrait.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PortraitXs>`
- `<$PortraitSm>`
- `<$PortraitMd>`
- `<$PortraitLg>`





## Portrait

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Portrait
include('material-4/Image/Portrait')

' renders the element
Portrait('Portrait', 'Portrait', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Portrait
include('material-4/Image/Portrait')

' renders the element
Portrait('Portrait', 'Portrait', 'an optional tech label', 'an optional description')
@enduml
```

