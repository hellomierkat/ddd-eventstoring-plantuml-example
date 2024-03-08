# Weebly


```text
fontawesome-6/Brands/Weebly
```

```text
include('fontawesome-6/Brands/Weebly')
```



| Illustration | Weebly |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Weebly.png) | ![illustration for Weebly](../../fontawesome-6/Brands/Weebly.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WeeblyXs>`
- `<$WeeblySm>`
- `<$WeeblyMd>`
- `<$WeeblyLg>`





## Weebly

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Weebly
include('fontawesome-6/Brands/Weebly')

' renders the element
Weebly('Weebly', 'Weebly', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Weebly
include('fontawesome-6/Brands/Weebly')

' renders the element
Weebly('Weebly', 'Weebly', 'an optional tech label', 'an optional description')
@enduml
```

