# EventSeat


```text
material-4/Action/EventSeat
```

```text
include('material-4/Action/EventSeat')
```



| Illustration | EventSeat |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/EventSeat.png) | ![illustration for EventSeat](../../material-4/Action/EventSeat.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EventSeatXs>`
- `<$EventSeatSm>`
- `<$EventSeatMd>`
- `<$EventSeatLg>`





## EventSeat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element EventSeat
include('material-4/Action/EventSeat')

' renders the element
EventSeat('EventSeat', 'Event Seat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element EventSeat
include('material-4/Action/EventSeat')

' renders the element
EventSeat('EventSeat', 'Event Seat', 'an optional tech label', 'an optional description')
@enduml
```

