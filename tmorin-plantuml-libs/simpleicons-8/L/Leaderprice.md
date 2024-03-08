# Leaderprice


```text
simpleicons-8/L/Leaderprice
```

```text
include('simpleicons-8/L/Leaderprice')
```



| Illustration | Leaderprice |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Leaderprice.png) | ![illustration for Leaderprice](../../simpleicons-8/L/Leaderprice.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LeaderpriceXs>`
- `<$LeaderpriceSm>`
- `<$LeaderpriceMd>`
- `<$LeaderpriceLg>`





## Leaderprice

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Leaderprice
include('simpleicons-8/L/Leaderprice')

' renders the element
Leaderprice('Leaderprice', 'Leaderprice', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Leaderprice
include('simpleicons-8/L/Leaderprice')

' renders the element
Leaderprice('Leaderprice', 'Leaderprice', 'an optional tech label', 'an optional description')
@enduml
```

