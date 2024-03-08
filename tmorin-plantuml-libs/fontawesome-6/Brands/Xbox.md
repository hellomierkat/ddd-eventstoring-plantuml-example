# Xbox


```text
fontawesome-6/Brands/Xbox
```

```text
include('fontawesome-6/Brands/Xbox')
```



| Illustration | Xbox |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Xbox.png) | ![illustration for Xbox](../../fontawesome-6/Brands/Xbox.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$XboxXs>`
- `<$XboxSm>`
- `<$XboxMd>`
- `<$XboxLg>`





## Xbox

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Xbox
include('fontawesome-6/Brands/Xbox')

' renders the element
Xbox('Xbox', 'Xbox', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Xbox
include('fontawesome-6/Brands/Xbox')

' renders the element
Xbox('Xbox', 'Xbox', 'an optional tech label', 'an optional description')
@enduml
```

