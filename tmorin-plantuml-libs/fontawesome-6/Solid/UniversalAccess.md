# UniversalAccess


```text
fontawesome-6/Solid/UniversalAccess
```

```text
include('fontawesome-6/Solid/UniversalAccess')
```



| Illustration | UniversalAccess |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/UniversalAccess.png) | ![illustration for UniversalAccess](../../fontawesome-6/Solid/UniversalAccess.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$UniversalAccessXs>`
- `<$UniversalAccessSm>`
- `<$UniversalAccessMd>`
- `<$UniversalAccessLg>`





## UniversalAccess

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element UniversalAccess
include('fontawesome-6/Solid/UniversalAccess')

' renders the element
UniversalAccess('UniversalAccess', 'Universal Access', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element UniversalAccess
include('fontawesome-6/Solid/UniversalAccess')

' renders the element
UniversalAccess('UniversalAccess', 'Universal Access', 'an optional tech label', 'an optional description')
@enduml
```

