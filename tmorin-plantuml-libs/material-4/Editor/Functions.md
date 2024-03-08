# Functions


```text
material-4/Editor/Functions
```

```text
include('material-4/Editor/Functions')
```



| Illustration | Functions |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/Functions.png) | ![illustration for Functions](../../material-4/Editor/Functions.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FunctionsXs>`
- `<$FunctionsSm>`
- `<$FunctionsMd>`
- `<$FunctionsLg>`





## Functions

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Functions
include('material-4/Editor/Functions')

' renders the element
Functions('Functions', 'Functions', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Functions
include('material-4/Editor/Functions')

' renders the element
Functions('Functions', 'Functions', 'an optional tech label', 'an optional description')
@enduml
```

