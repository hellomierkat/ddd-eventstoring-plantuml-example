# ArrowRight


```text
material-4/Navigation/ArrowRight
```

```text
include('material-4/Navigation/ArrowRight')
```



| Illustration | ArrowRight |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/ArrowRight.png) | ![illustration for ArrowRight](../../material-4/Navigation/ArrowRight.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ArrowRightXs>`
- `<$ArrowRightSm>`
- `<$ArrowRightMd>`
- `<$ArrowRightLg>`





## ArrowRight

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ArrowRight
include('material-4/Navigation/ArrowRight')

' renders the element
ArrowRight('ArrowRight', 'Arrow Right', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ArrowRight
include('material-4/Navigation/ArrowRight')

' renders the element
ArrowRight('ArrowRight', 'Arrow Right', 'an optional tech label', 'an optional description')
@enduml
```

