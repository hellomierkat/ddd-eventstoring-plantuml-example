# Stardock


```text
simpleicons-8/S/Stardock
```

```text
include('simpleicons-8/S/Stardock')
```



| Illustration | Stardock |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Stardock.png) | ![illustration for Stardock](../../simpleicons-8/S/Stardock.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$StardockXs>`
- `<$StardockSm>`
- `<$StardockMd>`
- `<$StardockLg>`





## Stardock

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Stardock
include('simpleicons-8/S/Stardock')

' renders the element
Stardock('Stardock', 'Stardock', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stardock
include('simpleicons-8/S/Stardock')

' renders the element
Stardock('Stardock', 'Stardock', 'an optional tech label', 'an optional description')
@enduml
```
