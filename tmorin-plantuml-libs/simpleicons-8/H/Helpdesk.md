# Helpdesk


```text
simpleicons-8/H/Helpdesk
```

```text
include('simpleicons-8/H/Helpdesk')
```



| Illustration | Helpdesk |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/H/Helpdesk.png) | ![illustration for Helpdesk](../../simpleicons-8/H/Helpdesk.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HelpdeskXs>`
- `<$HelpdeskSm>`
- `<$HelpdeskMd>`
- `<$HelpdeskLg>`





## Helpdesk

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Helpdesk
include('simpleicons-8/H/Helpdesk')

' renders the element
Helpdesk('Helpdesk', 'Helpdesk', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Helpdesk
include('simpleicons-8/H/Helpdesk')

' renders the element
Helpdesk('Helpdesk', 'Helpdesk', 'an optional tech label', 'an optional description')
@enduml
```

