# CardMembership


```text
material-4/Action/CardMembership
```

```text
include('material-4/Action/CardMembership')
```



| Illustration | CardMembership |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/CardMembership.png) | ![illustration for CardMembership](../../material-4/Action/CardMembership.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CardMembershipXs>`
- `<$CardMembershipSm>`
- `<$CardMembershipMd>`
- `<$CardMembershipLg>`





## CardMembership

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element CardMembership
include('material-4/Action/CardMembership')

' renders the element
CardMembership('CardMembership', 'Card Membership', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element CardMembership
include('material-4/Action/CardMembership')

' renders the element
CardMembership('CardMembership', 'Card Membership', 'an optional tech label', 'an optional description')
@enduml
```

