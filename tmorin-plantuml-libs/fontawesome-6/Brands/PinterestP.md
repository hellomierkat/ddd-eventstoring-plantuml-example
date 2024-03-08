# PinterestP


```text
fontawesome-6/Brands/PinterestP
```

```text
include('fontawesome-6/Brands/PinterestP')
```



| Illustration | PinterestP |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/PinterestP.png) | ![illustration for PinterestP](../../fontawesome-6/Brands/PinterestP.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PinterestPXs>`
- `<$PinterestPSm>`
- `<$PinterestPMd>`
- `<$PinterestPLg>`





## PinterestP

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PinterestP
include('fontawesome-6/Brands/PinterestP')

' renders the element
PinterestP('PinterestP', 'Pinterest P', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PinterestP
include('fontawesome-6/Brands/PinterestP')

' renders the element
PinterestP('PinterestP', 'Pinterest P', 'an optional tech label', 'an optional description')
@enduml
```

