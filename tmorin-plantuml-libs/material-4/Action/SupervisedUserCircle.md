# SupervisedUserCircle


```text
material-4/Action/SupervisedUserCircle
```

```text
include('material-4/Action/SupervisedUserCircle')
```



| Illustration | SupervisedUserCircle |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/SupervisedUserCircle.png) | ![illustration for SupervisedUserCircle](../../material-4/Action/SupervisedUserCircle.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SupervisedUserCircleXs>`
- `<$SupervisedUserCircleSm>`
- `<$SupervisedUserCircleMd>`
- `<$SupervisedUserCircleLg>`





## SupervisedUserCircle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SupervisedUserCircle
include('material-4/Action/SupervisedUserCircle')

' renders the element
SupervisedUserCircle('SupervisedUserCircle', 'Supervised User Circle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SupervisedUserCircle
include('material-4/Action/SupervisedUserCircle')

' renders the element
SupervisedUserCircle('SupervisedUserCircle', 'Supervised User Circle', 'an optional tech label', 'an optional description')
@enduml
```

