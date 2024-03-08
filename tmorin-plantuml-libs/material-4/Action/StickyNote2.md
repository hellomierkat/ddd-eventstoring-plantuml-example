# StickyNote2


```text
material-4/Action/StickyNote2
```

```text
include('material-4/Action/StickyNote2')
```



| Illustration | StickyNote2 |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/StickyNote2.png) | ![illustration for StickyNote2](../../material-4/Action/StickyNote2.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$StickyNote2Xs>`
- `<$StickyNote2Sm>`
- `<$StickyNote2Md>`
- `<$StickyNote2Lg>`





## StickyNote2

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element StickyNote2
include('material-4/Action/StickyNote2')

' renders the element
StickyNote2('StickyNote2', 'Sticky Note2', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element StickyNote2
include('material-4/Action/StickyNote2')

' renders the element
StickyNote2('StickyNote2', 'Sticky Note2', 'an optional tech label', 'an optional description')
@enduml
```

