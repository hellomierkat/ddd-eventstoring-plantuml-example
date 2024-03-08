# GooglePlusG


```text
fontawesome-6/Brands/GooglePlusG
```

```text
include('fontawesome-6/Brands/GooglePlusG')
```



| Illustration | GooglePlusG |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/GooglePlusG.png) | ![illustration for GooglePlusG](../../fontawesome-6/Brands/GooglePlusG.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GooglePlusGXs>`
- `<$GooglePlusGSm>`
- `<$GooglePlusGMd>`
- `<$GooglePlusGLg>`





## GooglePlusG

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GooglePlusG
include('fontawesome-6/Brands/GooglePlusG')

' renders the element
GooglePlusG('GooglePlusG', 'Google Plus G', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element GooglePlusG
include('fontawesome-6/Brands/GooglePlusG')

' renders the element
GooglePlusG('GooglePlusG', 'Google Plus G', 'an optional tech label', 'an optional description')
@enduml
```

