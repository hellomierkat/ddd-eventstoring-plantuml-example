# CorporateFare


```text
material-4/Places/CorporateFare
```

```text
include('material-4/Places/CorporateFare')
```



| Illustration | CorporateFare |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/CorporateFare.png) | ![illustration for CorporateFare](../../material-4/Places/CorporateFare.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CorporateFareXs>`
- `<$CorporateFareSm>`
- `<$CorporateFareMd>`
- `<$CorporateFareLg>`





## CorporateFare

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element CorporateFare
include('material-4/Places/CorporateFare')

' renders the element
CorporateFare('CorporateFare', 'Corporate Fare', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CorporateFare
include('material-4/Places/CorporateFare')

' renders the element
CorporateFare('CorporateFare', 'Corporate Fare', 'an optional tech label', 'an optional description')
@enduml
```

