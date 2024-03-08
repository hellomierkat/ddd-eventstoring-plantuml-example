# Forward


```text
fontawesome-6/Solid/Forward
```

```text
include('fontawesome-6/Solid/Forward')
```



| Illustration | Forward |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Forward.png) | ![illustration for Forward](../../fontawesome-6/Solid/Forward.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ForwardXs>`
- `<$ForwardSm>`
- `<$ForwardMd>`
- `<$ForwardLg>`





## Forward

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Forward
include('fontawesome-6/Solid/Forward')

' renders the element
Forward('Forward', 'Forward', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Forward
include('fontawesome-6/Solid/Forward')

' renders the element
Forward('Forward', 'Forward', 'an optional tech label', 'an optional description')
@enduml
```

