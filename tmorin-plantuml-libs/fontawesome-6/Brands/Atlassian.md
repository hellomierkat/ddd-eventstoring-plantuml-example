# Atlassian


```text
fontawesome-6/Brands/Atlassian
```

```text
include('fontawesome-6/Brands/Atlassian')
```



| Illustration | Atlassian |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Atlassian.png) | ![illustration for Atlassian](../../fontawesome-6/Brands/Atlassian.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AtlassianXs>`
- `<$AtlassianSm>`
- `<$AtlassianMd>`
- `<$AtlassianLg>`





## Atlassian

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Atlassian
include('fontawesome-6/Brands/Atlassian')

' renders the element
Atlassian('Atlassian', 'Atlassian', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Atlassian
include('fontawesome-6/Brands/Atlassian')

' renders the element
Atlassian('Atlassian', 'Atlassian', 'an optional tech label', 'an optional description')
@enduml
```

