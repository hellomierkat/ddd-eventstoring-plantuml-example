# NetworkWired


```text
fontawesome-6/Solid/NetworkWired
```

```text
include('fontawesome-6/Solid/NetworkWired')
```



| Illustration | NetworkWired |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/NetworkWired.png) | ![illustration for NetworkWired](../../fontawesome-6/Solid/NetworkWired.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$NetworkWiredXs>`
- `<$NetworkWiredSm>`
- `<$NetworkWiredMd>`
- `<$NetworkWiredLg>`





## NetworkWired

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element NetworkWired
include('fontawesome-6/Solid/NetworkWired')

' renders the element
NetworkWired('NetworkWired', 'Network Wired', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element NetworkWired
include('fontawesome-6/Solid/NetworkWired')

' renders the element
NetworkWired('NetworkWired', 'Network Wired', 'an optional tech label', 'an optional description')
@enduml
```

