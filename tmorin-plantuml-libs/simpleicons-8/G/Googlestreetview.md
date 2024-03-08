# Googlestreetview


```text
simpleicons-8/G/Googlestreetview
```

```text
include('simpleicons-8/G/Googlestreetview')
```



| Illustration | Googlestreetview |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Googlestreetview.png) | ![illustration for Googlestreetview](../../simpleicons-8/G/Googlestreetview.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GooglestreetviewXs>`
- `<$GooglestreetviewSm>`
- `<$GooglestreetviewMd>`
- `<$GooglestreetviewLg>`





## Googlestreetview

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Googlestreetview
include('simpleicons-8/G/Googlestreetview')

' renders the element
Googlestreetview('Googlestreetview', 'Googlestreetview', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Googlestreetview
include('simpleicons-8/G/Googlestreetview')

' renders the element
Googlestreetview('Googlestreetview', 'Googlestreetview', 'an optional tech label', 'an optional description')
@enduml
```

