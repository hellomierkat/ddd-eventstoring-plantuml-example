# OpenInFull


```text
material-4/Action/OpenInFull
```

```text
include('material-4/Action/OpenInFull')
```



| Illustration | OpenInFull |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/OpenInFull.png) | ![illustration for OpenInFull](../../material-4/Action/OpenInFull.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OpenInFullXs>`
- `<$OpenInFullSm>`
- `<$OpenInFullMd>`
- `<$OpenInFullLg>`





## OpenInFull

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element OpenInFull
include('material-4/Action/OpenInFull')

' renders the element
OpenInFull('OpenInFull', 'Open In Full', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element OpenInFull
include('material-4/Action/OpenInFull')

' renders the element
OpenInFull('OpenInFull', 'Open In Full', 'an optional tech label', 'an optional description')
@enduml
```

