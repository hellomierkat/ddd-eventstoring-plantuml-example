# Squarespace


```text
fontawesome-6/Brands/Squarespace
```

```text
include('fontawesome-6/Brands/Squarespace')
```



| Illustration | Squarespace |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Squarespace.png) | ![illustration for Squarespace](../../fontawesome-6/Brands/Squarespace.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SquarespaceXs>`
- `<$SquarespaceSm>`
- `<$SquarespaceMd>`
- `<$SquarespaceLg>`





## Squarespace

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Squarespace
include('fontawesome-6/Brands/Squarespace')

' renders the element
Squarespace('Squarespace', 'Squarespace', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Squarespace
include('fontawesome-6/Brands/Squarespace')

' renders the element
Squarespace('Squarespace', 'Squarespace', 'an optional tech label', 'an optional description')
@enduml
```

