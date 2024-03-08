# Gavel


```text
material-4/Action/Gavel
```

```text
include('material-4/Action/Gavel')
```



| Illustration | Gavel |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Gavel.png) | ![illustration for Gavel](../../material-4/Action/Gavel.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GavelXs>`
- `<$GavelSm>`
- `<$GavelMd>`
- `<$GavelLg>`





## Gavel

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Gavel
include('material-4/Action/Gavel')

' renders the element
Gavel('Gavel', 'Gavel', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gavel
include('material-4/Action/Gavel')

' renders the element
Gavel('Gavel', 'Gavel', 'an optional tech label', 'an optional description')
@enduml
```

