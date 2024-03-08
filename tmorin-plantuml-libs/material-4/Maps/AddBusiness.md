# AddBusiness


```text
material-4/Maps/AddBusiness
```

```text
include('material-4/Maps/AddBusiness')
```



| Illustration | AddBusiness |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/AddBusiness.png) | ![illustration for AddBusiness](../../material-4/Maps/AddBusiness.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddBusinessXs>`
- `<$AddBusinessSm>`
- `<$AddBusinessMd>`
- `<$AddBusinessLg>`





## AddBusiness

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element AddBusiness
include('material-4/Maps/AddBusiness')

' renders the element
AddBusiness('AddBusiness', 'Add Business', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AddBusiness
include('material-4/Maps/AddBusiness')

' renders the element
AddBusiness('AddBusiness', 'Add Business', 'an optional tech label', 'an optional description')
@enduml
```

