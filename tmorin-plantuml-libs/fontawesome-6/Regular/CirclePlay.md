# CirclePlay


```text
fontawesome-6/Regular/CirclePlay
```

```text
include('fontawesome-6/Regular/CirclePlay')
```



| Illustration | CirclePlay |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/CirclePlay.png) | ![illustration for CirclePlay](../../fontawesome-6/Regular/CirclePlay.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CirclePlayXs>`
- `<$CirclePlaySm>`
- `<$CirclePlayMd>`
- `<$CirclePlayLg>`





## CirclePlay

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CirclePlay
include('fontawesome-6/Regular/CirclePlay')

' renders the element
CirclePlay('CirclePlay', 'Circle Play', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CirclePlay
include('fontawesome-6/Regular/CirclePlay')

' renders the element
CirclePlay('CirclePlay', 'Circle Play', 'an optional tech label', 'an optional description')
@enduml
```

