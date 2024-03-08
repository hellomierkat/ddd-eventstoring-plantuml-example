# Fluxus


```text
simpleicons-8/F/Fluxus
```

```text
include('simpleicons-8/F/Fluxus')
```



| Illustration | Fluxus |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Fluxus.png) | ![illustration for Fluxus](../../simpleicons-8/F/Fluxus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FluxusXs>`
- `<$FluxusSm>`
- `<$FluxusMd>`
- `<$FluxusLg>`





## Fluxus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Fluxus
include('simpleicons-8/F/Fluxus')

' renders the element
Fluxus('Fluxus', 'Fluxus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fluxus
include('simpleicons-8/F/Fluxus')

' renders the element
Fluxus('Fluxus', 'Fluxus', 'an optional tech label', 'an optional description')
@enduml
```

