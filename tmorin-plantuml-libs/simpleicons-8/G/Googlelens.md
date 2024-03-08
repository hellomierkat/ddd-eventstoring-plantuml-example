# Googlelens


```text
simpleicons-8/G/Googlelens
```

```text
include('simpleicons-8/G/Googlelens')
```



| Illustration | Googlelens |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Googlelens.png) | ![illustration for Googlelens](../../simpleicons-8/G/Googlelens.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GooglelensXs>`
- `<$GooglelensSm>`
- `<$GooglelensMd>`
- `<$GooglelensLg>`





## Googlelens

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Googlelens
include('simpleicons-8/G/Googlelens')

' renders the element
Googlelens('Googlelens', 'Googlelens', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Googlelens
include('simpleicons-8/G/Googlelens')

' renders the element
Googlelens('Googlelens', 'Googlelens', 'an optional tech label', 'an optional description')
@enduml
```

