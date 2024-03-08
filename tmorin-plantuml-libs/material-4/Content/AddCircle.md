# AddCircle


```text
material-4/Content/AddCircle
```

```text
include('material-4/Content/AddCircle')
```



| Illustration | AddCircle |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/AddCircle.png) | ![illustration for AddCircle](../../material-4/Content/AddCircle.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddCircleXs>`
- `<$AddCircleSm>`
- `<$AddCircleMd>`
- `<$AddCircleLg>`





## AddCircle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AddCircle
include('material-4/Content/AddCircle')

' renders the element
AddCircle('AddCircle', 'Add Circle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AddCircle
include('material-4/Content/AddCircle')

' renders the element
AddCircle('AddCircle', 'Add Circle', 'an optional tech label', 'an optional description')
@enduml
```

