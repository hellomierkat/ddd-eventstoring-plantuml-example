# Eventbrite


```text
simpleicons-8/E/Eventbrite
```

```text
include('simpleicons-8/E/Eventbrite')
```



| Illustration | Eventbrite |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/E/Eventbrite.png) | ![illustration for Eventbrite](../../simpleicons-8/E/Eventbrite.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EventbriteXs>`
- `<$EventbriteSm>`
- `<$EventbriteMd>`
- `<$EventbriteLg>`





## Eventbrite

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Eventbrite
include('simpleicons-8/E/Eventbrite')

' renders the element
Eventbrite('Eventbrite', 'Eventbrite', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Eventbrite
include('simpleicons-8/E/Eventbrite')

' renders the element
Eventbrite('Eventbrite', 'Eventbrite', 'an optional tech label', 'an optional description')
@enduml
```

