# Aerlingus


```text
simpleicons-8/A/Aerlingus
```

```text
include('simpleicons-8/A/Aerlingus')
```



| Illustration | Aerlingus |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Aerlingus.png) | ![illustration for Aerlingus](../../simpleicons-8/A/Aerlingus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AerlingusXs>`
- `<$AerlingusSm>`
- `<$AerlingusMd>`
- `<$AerlingusLg>`





## Aerlingus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Aerlingus
include('simpleicons-8/A/Aerlingus')

' renders the element
Aerlingus('Aerlingus', 'Aerlingus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Aerlingus
include('simpleicons-8/A/Aerlingus')

' renders the element
Aerlingus('Aerlingus', 'Aerlingus', 'an optional tech label', 'an optional description')
@enduml
```

