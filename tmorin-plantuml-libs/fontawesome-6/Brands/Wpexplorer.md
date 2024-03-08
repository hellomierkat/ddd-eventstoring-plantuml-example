# Wpexplorer


```text
fontawesome-6/Brands/Wpexplorer
```

```text
include('fontawesome-6/Brands/Wpexplorer')
```



| Illustration | Wpexplorer |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Wpexplorer.png) | ![illustration for Wpexplorer](../../fontawesome-6/Brands/Wpexplorer.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WpexplorerXs>`
- `<$WpexplorerSm>`
- `<$WpexplorerMd>`
- `<$WpexplorerLg>`





## Wpexplorer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Wpexplorer
include('fontawesome-6/Brands/Wpexplorer')

' renders the element
Wpexplorer('Wpexplorer', 'Wpexplorer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wpexplorer
include('fontawesome-6/Brands/Wpexplorer')

' renders the element
Wpexplorer('Wpexplorer', 'Wpexplorer', 'an optional tech label', 'an optional description')
@enduml
```

