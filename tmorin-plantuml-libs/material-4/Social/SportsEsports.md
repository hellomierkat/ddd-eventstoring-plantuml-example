# SportsEsports


```text
material-4/Social/SportsEsports
```

```text
include('material-4/Social/SportsEsports')
```



| Illustration | SportsEsports |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/SportsEsports.png) | ![illustration for SportsEsports](../../material-4/Social/SportsEsports.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SportsEsportsXs>`
- `<$SportsEsportsSm>`
- `<$SportsEsportsMd>`
- `<$SportsEsportsLg>`





## SportsEsports

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SportsEsports
include('material-4/Social/SportsEsports')

' renders the element
SportsEsports('SportsEsports', 'Sports Esports', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SportsEsports
include('material-4/Social/SportsEsports')

' renders the element
SportsEsports('SportsEsports', 'Sports Esports', 'an optional tech label', 'an optional description')
@enduml
```

