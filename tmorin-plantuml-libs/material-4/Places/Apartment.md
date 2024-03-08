# Apartment


```text
material-4/Places/Apartment
```

```text
include('material-4/Places/Apartment')
```



| Illustration | Apartment |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/Apartment.png) | ![illustration for Apartment](../../material-4/Places/Apartment.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ApartmentXs>`
- `<$ApartmentSm>`
- `<$ApartmentMd>`
- `<$ApartmentLg>`





## Apartment

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Apartment
include('material-4/Places/Apartment')

' renders the element
Apartment('Apartment', 'Apartment', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Apartment
include('material-4/Places/Apartment')

' renders the element
Apartment('Apartment', 'Apartment', 'an optional tech label', 'an optional description')
@enduml
```

