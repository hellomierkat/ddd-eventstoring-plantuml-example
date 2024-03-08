# Hornbill


```text
fontawesome-6/Brands/Hornbill
```

```text
include('fontawesome-6/Brands/Hornbill')
```



| Illustration | Hornbill |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Hornbill.png) | ![illustration for Hornbill](../../fontawesome-6/Brands/Hornbill.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HornbillXs>`
- `<$HornbillSm>`
- `<$HornbillMd>`
- `<$HornbillLg>`





## Hornbill

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Hornbill
include('fontawesome-6/Brands/Hornbill')

' renders the element
Hornbill('Hornbill', 'Hornbill', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Hornbill
include('fontawesome-6/Brands/Hornbill')

' renders the element
Hornbill('Hornbill', 'Hornbill', 'an optional tech label', 'an optional description')
@enduml
```

