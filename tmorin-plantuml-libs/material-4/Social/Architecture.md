# Architecture


```text
material-4/Social/Architecture
```

```text
include('material-4/Social/Architecture')
```



| Illustration | Architecture |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/Architecture.png) | ![illustration for Architecture](../../material-4/Social/Architecture.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ArchitectureXs>`
- `<$ArchitectureSm>`
- `<$ArchitectureMd>`
- `<$ArchitectureLg>`





## Architecture

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Architecture
include('material-4/Social/Architecture')

' renders the element
Architecture('Architecture', 'Architecture', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Architecture
include('material-4/Social/Architecture')

' renders the element
Architecture('Architecture', 'Architecture', 'an optional tech label', 'an optional description')
@enduml
```

