# Lbry


```text
simpleicons-8/L/Lbry
```

```text
include('simpleicons-8/L/Lbry')
```



| Illustration | Lbry |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Lbry.png) | ![illustration for Lbry](../../simpleicons-8/L/Lbry.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LbryXs>`
- `<$LbrySm>`
- `<$LbryMd>`
- `<$LbryLg>`





## Lbry

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Lbry
include('simpleicons-8/L/Lbry')

' renders the element
Lbry('Lbry', 'Lbry', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Lbry
include('simpleicons-8/L/Lbry')

' renders the element
Lbry('Lbry', 'Lbry', 'an optional tech label', 'an optional description')
@enduml
```

