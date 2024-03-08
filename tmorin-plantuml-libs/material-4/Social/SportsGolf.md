# SportsGolf


```text
material-4/Social/SportsGolf
```

```text
include('material-4/Social/SportsGolf')
```



| Illustration | SportsGolf |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/SportsGolf.png) | ![illustration for SportsGolf](../../material-4/Social/SportsGolf.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SportsGolfXs>`
- `<$SportsGolfSm>`
- `<$SportsGolfMd>`
- `<$SportsGolfLg>`





## SportsGolf

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SportsGolf
include('material-4/Social/SportsGolf')

' renders the element
SportsGolf('SportsGolf', 'Sports Golf', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SportsGolf
include('material-4/Social/SportsGolf')

' renders the element
SportsGolf('SportsGolf', 'Sports Golf', 'an optional tech label', 'an optional description')
@enduml
```

