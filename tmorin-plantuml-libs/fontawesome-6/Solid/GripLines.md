# GripLines


```text
fontawesome-6/Solid/GripLines
```

```text
include('fontawesome-6/Solid/GripLines')
```



| Illustration | GripLines |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/GripLines.png) | ![illustration for GripLines](../../fontawesome-6/Solid/GripLines.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GripLinesXs>`
- `<$GripLinesSm>`
- `<$GripLinesMd>`
- `<$GripLinesLg>`





## GripLines

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GripLines
include('fontawesome-6/Solid/GripLines')

' renders the element
GripLines('GripLines', 'Grip Lines', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GripLines
include('fontawesome-6/Solid/GripLines')

' renders the element
GripLines('GripLines', 'Grip Lines', 'an optional tech label', 'an optional description')
@enduml
```

