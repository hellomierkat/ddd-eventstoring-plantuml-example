# Steamworks


```text
simpleicons-8/S/Steamworks
```

```text
include('simpleicons-8/S/Steamworks')
```



| Illustration | Steamworks |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Steamworks.png) | ![illustration for Steamworks](../../simpleicons-8/S/Steamworks.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SteamworksXs>`
- `<$SteamworksSm>`
- `<$SteamworksMd>`
- `<$SteamworksLg>`





## Steamworks

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Steamworks
include('simpleicons-8/S/Steamworks')

' renders the element
Steamworks('Steamworks', 'Steamworks', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Steamworks
include('simpleicons-8/S/Steamworks')

' renders the element
Steamworks('Steamworks', 'Steamworks', 'an optional tech label', 'an optional description')
@enduml
```

