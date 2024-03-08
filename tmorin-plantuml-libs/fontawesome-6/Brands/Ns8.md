# Ns8


```text
fontawesome-6/Brands/Ns8
```

```text
include('fontawesome-6/Brands/Ns8')
```



| Illustration | Ns8 |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Ns8.png) | ![illustration for Ns8](../../fontawesome-6/Brands/Ns8.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Ns8Xs>`
- `<$Ns8Sm>`
- `<$Ns8Md>`
- `<$Ns8Lg>`





## Ns8

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Ns8
include('fontawesome-6/Brands/Ns8')

' renders the element
Ns8('Ns8', 'Ns8', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ns8
include('fontawesome-6/Brands/Ns8')

' renders the element
Ns8('Ns8', 'Ns8', 'an optional tech label', 'an optional description')
@enduml
```

