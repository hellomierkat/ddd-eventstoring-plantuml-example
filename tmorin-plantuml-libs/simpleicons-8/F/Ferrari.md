# Ferrari


```text
simpleicons-8/F/Ferrari
```

```text
include('simpleicons-8/F/Ferrari')
```



| Illustration | Ferrari |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Ferrari.png) | ![illustration for Ferrari](../../simpleicons-8/F/Ferrari.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FerrariXs>`
- `<$FerrariSm>`
- `<$FerrariMd>`
- `<$FerrariLg>`





## Ferrari

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ferrari
include('simpleicons-8/F/Ferrari')

' renders the element
Ferrari('Ferrari', 'Ferrari', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ferrari
include('simpleicons-8/F/Ferrari')

' renders the element
Ferrari('Ferrari', 'Ferrari', 'an optional tech label', 'an optional description')
@enduml
```

