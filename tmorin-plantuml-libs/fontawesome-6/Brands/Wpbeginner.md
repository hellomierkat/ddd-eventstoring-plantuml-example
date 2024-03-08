# Wpbeginner


```text
fontawesome-6/Brands/Wpbeginner
```

```text
include('fontawesome-6/Brands/Wpbeginner')
```



| Illustration | Wpbeginner |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Wpbeginner.png) | ![illustration for Wpbeginner](../../fontawesome-6/Brands/Wpbeginner.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WpbeginnerXs>`
- `<$WpbeginnerSm>`
- `<$WpbeginnerMd>`
- `<$WpbeginnerLg>`





## Wpbeginner

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Wpbeginner
include('fontawesome-6/Brands/Wpbeginner')

' renders the element
Wpbeginner('Wpbeginner', 'Wpbeginner', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wpbeginner
include('fontawesome-6/Brands/Wpbeginner')

' renders the element
Wpbeginner('Wpbeginner', 'Wpbeginner', 'an optional tech label', 'an optional description')
@enduml
```

