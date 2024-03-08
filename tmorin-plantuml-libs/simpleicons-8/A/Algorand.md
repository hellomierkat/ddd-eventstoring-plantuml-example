# Algorand


```text
simpleicons-8/A/Algorand
```

```text
include('simpleicons-8/A/Algorand')
```



| Illustration | Algorand |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Algorand.png) | ![illustration for Algorand](../../simpleicons-8/A/Algorand.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AlgorandXs>`
- `<$AlgorandSm>`
- `<$AlgorandMd>`
- `<$AlgorandLg>`





## Algorand

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Algorand
include('simpleicons-8/A/Algorand')

' renders the element
Algorand('Algorand', 'Algorand', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Algorand
include('simpleicons-8/A/Algorand')

' renders the element
Algorand('Algorand', 'Algorand', 'an optional tech label', 'an optional description')
@enduml
```

