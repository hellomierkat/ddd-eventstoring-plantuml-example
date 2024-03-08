# Garmin


```text
simpleicons-8/G/Garmin
```

```text
include('simpleicons-8/G/Garmin')
```



| Illustration | Garmin |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Garmin.png) | ![illustration for Garmin](../../simpleicons-8/G/Garmin.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GarminXs>`
- `<$GarminSm>`
- `<$GarminMd>`
- `<$GarminLg>`





## Garmin

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Garmin
include('simpleicons-8/G/Garmin')

' renders the element
Garmin('Garmin', 'Garmin', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Garmin
include('simpleicons-8/G/Garmin')

' renders the element
Garmin('Garmin', 'Garmin', 'an optional tech label', 'an optional description')
@enduml
```

