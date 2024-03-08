# Firstdraft


```text
fontawesome-6/Brands/Firstdraft
```

```text
include('fontawesome-6/Brands/Firstdraft')
```



| Illustration | Firstdraft |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Firstdraft.png) | ![illustration for Firstdraft](../../fontawesome-6/Brands/Firstdraft.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FirstdraftXs>`
- `<$FirstdraftSm>`
- `<$FirstdraftMd>`
- `<$FirstdraftLg>`





## Firstdraft

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Firstdraft
include('fontawesome-6/Brands/Firstdraft')

' renders the element
Firstdraft('Firstdraft', 'Firstdraft', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Firstdraft
include('fontawesome-6/Brands/Firstdraft')

' renders the element
Firstdraft('Firstdraft', 'Firstdraft', 'an optional tech label', 'an optional description')
@enduml
```

