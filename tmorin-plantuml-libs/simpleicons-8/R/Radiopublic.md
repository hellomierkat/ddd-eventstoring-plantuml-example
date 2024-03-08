# Radiopublic


```text
simpleicons-8/R/Radiopublic
```

```text
include('simpleicons-8/R/Radiopublic')
```



| Illustration | Radiopublic |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Radiopublic.png) | ![illustration for Radiopublic](../../simpleicons-8/R/Radiopublic.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RadiopublicXs>`
- `<$RadiopublicSm>`
- `<$RadiopublicMd>`
- `<$RadiopublicLg>`





## Radiopublic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Radiopublic
include('simpleicons-8/R/Radiopublic')

' renders the element
Radiopublic('Radiopublic', 'Radiopublic', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Radiopublic
include('simpleicons-8/R/Radiopublic')

' renders the element
Radiopublic('Radiopublic', 'Radiopublic', 'an optional tech label', 'an optional description')
@enduml
```

