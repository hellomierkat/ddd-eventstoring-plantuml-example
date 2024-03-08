# Sd


```text
material-4/Av/Sd
```

```text
include('material-4/Av/Sd')
```



| Illustration | Sd |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/Sd.png) | ![illustration for Sd](../../material-4/Av/Sd.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SdXs>`
- `<$SdSm>`
- `<$SdMd>`
- `<$SdLg>`





## Sd

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Sd
include('material-4/Av/Sd')

' renders the element
Sd('Sd', 'Sd', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sd
include('material-4/Av/Sd')

' renders the element
Sd('Sd', 'Sd', 'an optional tech label', 'an optional description')
@enduml
```

