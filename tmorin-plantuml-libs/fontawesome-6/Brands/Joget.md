# Joget


```text
fontawesome-6/Brands/Joget
```

```text
include('fontawesome-6/Brands/Joget')
```



| Illustration | Joget |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Joget.png) | ![illustration for Joget](../../fontawesome-6/Brands/Joget.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JogetXs>`
- `<$JogetSm>`
- `<$JogetMd>`
- `<$JogetLg>`





## Joget

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Joget
include('fontawesome-6/Brands/Joget')

' renders the element
Joget('Joget', 'Joget', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Joget
include('fontawesome-6/Brands/Joget')

' renders the element
Joget('Joget', 'Joget', 'an optional tech label', 'an optional description')
@enduml
```

