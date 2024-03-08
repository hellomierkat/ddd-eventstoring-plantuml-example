# CloudCircle


```text
material-4/File/CloudCircle
```

```text
include('material-4/File/CloudCircle')
```



| Illustration | CloudCircle |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/File/CloudCircle.png) | ![illustration for CloudCircle](../../material-4/File/CloudCircle.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CloudCircleXs>`
- `<$CloudCircleSm>`
- `<$CloudCircleMd>`
- `<$CloudCircleLg>`





## CloudCircle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element CloudCircle
include('material-4/File/CloudCircle')

' renders the element
CloudCircle('CloudCircle', 'Cloud Circle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CloudCircle
include('material-4/File/CloudCircle')

' renders the element
CloudCircle('CloudCircle', 'Cloud Circle', 'an optional tech label', 'an optional description')
@enduml
```

