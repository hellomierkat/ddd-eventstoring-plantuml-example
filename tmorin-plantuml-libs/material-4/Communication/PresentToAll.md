# PresentToAll


```text
material-4/Communication/PresentToAll
```

```text
include('material-4/Communication/PresentToAll')
```



| Illustration | PresentToAll |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/PresentToAll.png) | ![illustration for PresentToAll](../../material-4/Communication/PresentToAll.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PresentToAllXs>`
- `<$PresentToAllSm>`
- `<$PresentToAllMd>`
- `<$PresentToAllLg>`





## PresentToAll

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PresentToAll
include('material-4/Communication/PresentToAll')

' renders the element
PresentToAll('PresentToAll', 'Present To All', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PresentToAll
include('material-4/Communication/PresentToAll')

' renders the element
PresentToAll('PresentToAll', 'Present To All', 'an optional tech label', 'an optional description')
@enduml
```

