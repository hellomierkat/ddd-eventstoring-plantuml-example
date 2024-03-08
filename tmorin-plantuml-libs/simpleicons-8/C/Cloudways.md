# Cloudways


```text
simpleicons-8/C/Cloudways
```

```text
include('simpleicons-8/C/Cloudways')
```



| Illustration | Cloudways |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Cloudways.png) | ![illustration for Cloudways](../../simpleicons-8/C/Cloudways.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CloudwaysXs>`
- `<$CloudwaysSm>`
- `<$CloudwaysMd>`
- `<$CloudwaysLg>`





## Cloudways

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Cloudways
include('simpleicons-8/C/Cloudways')

' renders the element
Cloudways('Cloudways', 'Cloudways', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cloudways
include('simpleicons-8/C/Cloudways')

' renders the element
Cloudways('Cloudways', 'Cloudways', 'an optional tech label', 'an optional description')
@enduml
```

