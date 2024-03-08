# DiscFull


```text
material-4/Notification/DiscFull
```

```text
include('material-4/Notification/DiscFull')
```



| Illustration | DiscFull |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Notification/DiscFull.png) | ![illustration for DiscFull](../../material-4/Notification/DiscFull.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DiscFullXs>`
- `<$DiscFullSm>`
- `<$DiscFullMd>`
- `<$DiscFullLg>`





## DiscFull

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DiscFull
include('material-4/Notification/DiscFull')

' renders the element
DiscFull('DiscFull', 'Disc Full', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DiscFull
include('material-4/Notification/DiscFull')

' renders the element
DiscFull('DiscFull', 'Disc Full', 'an optional tech label', 'an optional description')
@enduml
```

