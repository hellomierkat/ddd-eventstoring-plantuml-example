# Draft2Digital


```text
fontawesome-6/Brands/Draft2Digital
```

```text
include('fontawesome-6/Brands/Draft2Digital')
```



| Illustration | Draft2Digital |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Draft2Digital.png) | ![illustration for Draft2Digital](../../fontawesome-6/Brands/Draft2Digital.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Draft2DigitalXs>`
- `<$Draft2DigitalSm>`
- `<$Draft2DigitalMd>`
- `<$Draft2DigitalLg>`





## Draft2Digital

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Draft2Digital
include('fontawesome-6/Brands/Draft2Digital')

' renders the element
Draft2Digital('Draft2Digital', 'Draft2 Digital', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Draft2Digital
include('fontawesome-6/Brands/Draft2Digital')

' renders the element
Draft2Digital('Draft2Digital', 'Draft2 Digital', 'an optional tech label', 'an optional description')
@enduml
```

