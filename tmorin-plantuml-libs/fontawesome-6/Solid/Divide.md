# Divide


```text
fontawesome-6/Solid/Divide
```

```text
include('fontawesome-6/Solid/Divide')
```



| Illustration | Divide |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Divide.png) | ![illustration for Divide](../../fontawesome-6/Solid/Divide.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DivideXs>`
- `<$DivideSm>`
- `<$DivideMd>`
- `<$DivideLg>`





## Divide

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Divide
include('fontawesome-6/Solid/Divide')

' renders the element
Divide('Divide', 'Divide', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Divide
include('fontawesome-6/Solid/Divide')

' renders the element
Divide('Divide', 'Divide', 'an optional tech label', 'an optional description')
@enduml
```

