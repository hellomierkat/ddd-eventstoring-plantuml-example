# Bedtime


```text
material-4/Image/Bedtime
```

```text
include('material-4/Image/Bedtime')
```



| Illustration | Bedtime |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Bedtime.png) | ![illustration for Bedtime](../../material-4/Image/Bedtime.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BedtimeXs>`
- `<$BedtimeSm>`
- `<$BedtimeMd>`
- `<$BedtimeLg>`





## Bedtime

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Bedtime
include('material-4/Image/Bedtime')

' renders the element
Bedtime('Bedtime', 'Bedtime', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bedtime
include('material-4/Image/Bedtime')

' renders the element
Bedtime('Bedtime', 'Bedtime', 'an optional tech label', 'an optional description')
@enduml
```

