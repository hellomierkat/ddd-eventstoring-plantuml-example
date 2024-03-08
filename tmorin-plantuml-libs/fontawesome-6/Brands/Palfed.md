# Palfed


```text
fontawesome-6/Brands/Palfed
```

```text
include('fontawesome-6/Brands/Palfed')
```



| Illustration | Palfed |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Palfed.png) | ![illustration for Palfed](../../fontawesome-6/Brands/Palfed.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PalfedXs>`
- `<$PalfedSm>`
- `<$PalfedMd>`
- `<$PalfedLg>`





## Palfed

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Palfed
include('fontawesome-6/Brands/Palfed')

' renders the element
Palfed('Palfed', 'Palfed', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Palfed
include('fontawesome-6/Brands/Palfed')

' renders the element
Palfed('Palfed', 'Palfed', 'an optional tech label', 'an optional description')
@enduml
```

