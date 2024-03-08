# LocalPharmacy


```text
material-4/Maps/LocalPharmacy
```

```text
include('material-4/Maps/LocalPharmacy')
```



| Illustration | LocalPharmacy |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/LocalPharmacy.png) | ![illustration for LocalPharmacy](../../material-4/Maps/LocalPharmacy.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LocalPharmacyXs>`
- `<$LocalPharmacySm>`
- `<$LocalPharmacyMd>`
- `<$LocalPharmacyLg>`





## LocalPharmacy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LocalPharmacy
include('material-4/Maps/LocalPharmacy')

' renders the element
LocalPharmacy('LocalPharmacy', 'Local Pharmacy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LocalPharmacy
include('material-4/Maps/LocalPharmacy')

' renders the element
LocalPharmacy('LocalPharmacy', 'Local Pharmacy', 'an optional tech label', 'an optional description')
@enduml
```

