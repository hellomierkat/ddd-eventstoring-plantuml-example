# Cocoapods


```text
simpleicons-8/C/Cocoapods
```

```text
include('simpleicons-8/C/Cocoapods')
```



| Illustration | Cocoapods |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Cocoapods.png) | ![illustration for Cocoapods](../../simpleicons-8/C/Cocoapods.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CocoapodsXs>`
- `<$CocoapodsSm>`
- `<$CocoapodsMd>`
- `<$CocoapodsLg>`





## Cocoapods

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Cocoapods
include('simpleicons-8/C/Cocoapods')

' renders the element
Cocoapods('Cocoapods', 'Cocoapods', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cocoapods
include('simpleicons-8/C/Cocoapods')

' renders the element
Cocoapods('Cocoapods', 'Cocoapods', 'an optional tech label', 'an optional description')
@enduml
```

