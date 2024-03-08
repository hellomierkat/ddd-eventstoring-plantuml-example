# DoNotTouch


```text
material-4/Places/DoNotTouch
```

```text
include('material-4/Places/DoNotTouch')
```



| Illustration | DoNotTouch |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/DoNotTouch.png) | ![illustration for DoNotTouch](../../material-4/Places/DoNotTouch.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DoNotTouchXs>`
- `<$DoNotTouchSm>`
- `<$DoNotTouchMd>`
- `<$DoNotTouchLg>`





## DoNotTouch

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DoNotTouch
include('material-4/Places/DoNotTouch')

' renders the element
DoNotTouch('DoNotTouch', 'Do Not Touch', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DoNotTouch
include('material-4/Places/DoNotTouch')

' renders the element
DoNotTouch('DoNotTouch', 'Do Not Touch', 'an optional tech label', 'an optional description')
@enduml
```

