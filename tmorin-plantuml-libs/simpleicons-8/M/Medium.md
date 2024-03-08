# Medium


```text
simpleicons-8/M/Medium
```

```text
include('simpleicons-8/M/Medium')
```



| Illustration | Medium |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Medium.png) | ![illustration for Medium](../../simpleicons-8/M/Medium.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MediumXs>`
- `<$MediumSm>`
- `<$MediumMd>`
- `<$MediumLg>`





## Medium

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Medium
include('simpleicons-8/M/Medium')

' renders the element
Medium('Medium', 'Medium', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Medium
include('simpleicons-8/M/Medium')

' renders the element
Medium('Medium', 'Medium', 'an optional tech label', 'an optional description')
@enduml
```

