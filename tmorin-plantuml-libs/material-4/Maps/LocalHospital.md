# LocalHospital


```text
material-4/Maps/LocalHospital
```

```text
include('material-4/Maps/LocalHospital')
```



| Illustration | LocalHospital |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/LocalHospital.png) | ![illustration for LocalHospital](../../material-4/Maps/LocalHospital.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LocalHospitalXs>`
- `<$LocalHospitalSm>`
- `<$LocalHospitalMd>`
- `<$LocalHospitalLg>`





## LocalHospital

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LocalHospital
include('material-4/Maps/LocalHospital')

' renders the element
LocalHospital('LocalHospital', 'Local Hospital', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LocalHospital
include('material-4/Maps/LocalHospital')

' renders the element
LocalHospital('LocalHospital', 'Local Hospital', 'an optional tech label', 'an optional description')
@enduml
```

