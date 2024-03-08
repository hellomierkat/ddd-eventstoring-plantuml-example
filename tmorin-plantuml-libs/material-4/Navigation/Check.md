# Check


```text
material-4/Navigation/Check
```

```text
include('material-4/Navigation/Check')
```



| Illustration | Check |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/Check.png) | ![illustration for Check](../../material-4/Navigation/Check.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CheckXs>`
- `<$CheckSm>`
- `<$CheckMd>`
- `<$CheckLg>`





## Check

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Check
include('material-4/Navigation/Check')

' renders the element
Check('Check', 'Check', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Check
include('material-4/Navigation/Check')

' renders the element
Check('Check', 'Check', 'an optional tech label', 'an optional description')
@enduml
```

