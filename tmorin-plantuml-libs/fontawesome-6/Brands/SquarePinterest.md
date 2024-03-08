# SquarePinterest


```text
fontawesome-6/Brands/SquarePinterest
```

```text
include('fontawesome-6/Brands/SquarePinterest')
```



| Illustration | SquarePinterest |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/SquarePinterest.png) | ![illustration for SquarePinterest](../../fontawesome-6/Brands/SquarePinterest.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SquarePinterestXs>`
- `<$SquarePinterestSm>`
- `<$SquarePinterestMd>`
- `<$SquarePinterestLg>`





## SquarePinterest

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element SquarePinterest
include('fontawesome-6/Brands/SquarePinterest')

' renders the element
SquarePinterest('SquarePinterest', 'Square Pinterest', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SquarePinterest
include('fontawesome-6/Brands/SquarePinterest')

' renders the element
SquarePinterest('SquarePinterest', 'Square Pinterest', 'an optional tech label', 'an optional description')
@enduml
```

