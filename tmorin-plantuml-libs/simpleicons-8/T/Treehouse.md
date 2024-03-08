# Treehouse


```text
simpleicons-8/T/Treehouse
```

```text
include('simpleicons-8/T/Treehouse')
```



| Illustration | Treehouse |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Treehouse.png) | ![illustration for Treehouse](../../simpleicons-8/T/Treehouse.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TreehouseXs>`
- `<$TreehouseSm>`
- `<$TreehouseMd>`
- `<$TreehouseLg>`





## Treehouse

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Treehouse
include('simpleicons-8/T/Treehouse')

' renders the element
Treehouse('Treehouse', 'Treehouse', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Treehouse
include('simpleicons-8/T/Treehouse')

' renders the element
Treehouse('Treehouse', 'Treehouse', 'an optional tech label', 'an optional description')
@enduml
```

