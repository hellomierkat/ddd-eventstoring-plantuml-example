# TruckPickup


```text
fontawesome-6/Solid/TruckPickup
```

```text
include('fontawesome-6/Solid/TruckPickup')
```



| Illustration | TruckPickup |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/TruckPickup.png) | ![illustration for TruckPickup](../../fontawesome-6/Solid/TruckPickup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TruckPickupXs>`
- `<$TruckPickupSm>`
- `<$TruckPickupMd>`
- `<$TruckPickupLg>`





## TruckPickup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TruckPickup
include('fontawesome-6/Solid/TruckPickup')

' renders the element
TruckPickup('TruckPickup', 'Truck Pickup', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TruckPickup
include('fontawesome-6/Solid/TruckPickup')

' renders the element
TruckPickup('TruckPickup', 'Truck Pickup', 'an optional tech label', 'an optional description')
@enduml
```

