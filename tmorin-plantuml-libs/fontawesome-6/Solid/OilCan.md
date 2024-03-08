# OilCan


```text
fontawesome-6/Solid/OilCan
```

```text
include('fontawesome-6/Solid/OilCan')
```



| Illustration | OilCan |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/OilCan.png) | ![illustration for OilCan](../../fontawesome-6/Solid/OilCan.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OilCanXs>`
- `<$OilCanSm>`
- `<$OilCanMd>`
- `<$OilCanLg>`





## OilCan

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element OilCan
include('fontawesome-6/Solid/OilCan')

' renders the element
OilCan('OilCan', 'Oil Can', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element OilCan
include('fontawesome-6/Solid/OilCan')

' renders the element
OilCan('OilCan', 'Oil Can', 'an optional tech label', 'an optional description')
@enduml
```

