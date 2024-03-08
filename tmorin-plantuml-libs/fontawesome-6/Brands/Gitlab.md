# Gitlab


```text
fontawesome-6/Brands/Gitlab
```

```text
include('fontawesome-6/Brands/Gitlab')
```



| Illustration | Gitlab |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Gitlab.png) | ![illustration for Gitlab](../../fontawesome-6/Brands/Gitlab.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GitlabXs>`
- `<$GitlabSm>`
- `<$GitlabMd>`
- `<$GitlabLg>`





## Gitlab

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Gitlab
include('fontawesome-6/Brands/Gitlab')

' renders the element
Gitlab('Gitlab', 'Gitlab', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gitlab
include('fontawesome-6/Brands/Gitlab')

' renders the element
Gitlab('Gitlab', 'Gitlab', 'an optional tech label', 'an optional description')
@enduml
```

