# Avianex


```text
fontawesome-6/Brands/Avianex
```

```text
include('fontawesome-6/Brands/Avianex')
```



| Illustration | Avianex |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Avianex.png) | ![illustration for Avianex](../../fontawesome-6/Brands/Avianex.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AvianexXs>`
- `<$AvianexSm>`
- `<$AvianexMd>`
- `<$AvianexLg>`





## Avianex

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Avianex
include('fontawesome-6/Brands/Avianex')

' renders the element
Avianex('Avianex', 'Avianex', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Avianex
include('fontawesome-6/Brands/Avianex')

' renders the element
Avianex('Avianex', 'Avianex', 'an optional tech label', 'an optional description')
@enduml
```

