# DataUsage


```text
material-4/Device/DataUsage
```

```text
include('material-4/Device/DataUsage')
```



| Illustration | DataUsage |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/DataUsage.png) | ![illustration for DataUsage](../../material-4/Device/DataUsage.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DataUsageXs>`
- `<$DataUsageSm>`
- `<$DataUsageMd>`
- `<$DataUsageLg>`





## DataUsage

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element DataUsage
include('material-4/Device/DataUsage')

' renders the element
DataUsage('DataUsage', 'Data Usage', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DataUsage
include('material-4/Device/DataUsage')

' renders the element
DataUsage('DataUsage', 'Data Usage', 'an optional tech label', 'an optional description')
@enduml
```

