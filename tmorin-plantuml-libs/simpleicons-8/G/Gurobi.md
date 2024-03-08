# Gurobi


```text
simpleicons-8/G/Gurobi
```

```text
include('simpleicons-8/G/Gurobi')
```



| Illustration | Gurobi |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gurobi.png) | ![illustration for Gurobi](../../simpleicons-8/G/Gurobi.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GurobiXs>`
- `<$GurobiSm>`
- `<$GurobiMd>`
- `<$GurobiLg>`





## Gurobi

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gurobi
include('simpleicons-8/G/Gurobi')

' renders the element
Gurobi('Gurobi', 'Gurobi', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gurobi
include('simpleicons-8/G/Gurobi')

' renders the element
Gurobi('Gurobi', 'Gurobi', 'an optional tech label', 'an optional description')
@enduml
```

