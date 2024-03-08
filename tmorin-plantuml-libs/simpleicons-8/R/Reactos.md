# Reactos


```text
simpleicons-8/R/Reactos
```

```text
include('simpleicons-8/R/Reactos')
```



| Illustration | Reactos |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Reactos.png) | ![illustration for Reactos](../../simpleicons-8/R/Reactos.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReactosXs>`
- `<$ReactosSm>`
- `<$ReactosMd>`
- `<$ReactosLg>`





## Reactos

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Reactos
include('simpleicons-8/R/Reactos')

' renders the element
Reactos('Reactos', 'Reactos', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reactos
include('simpleicons-8/R/Reactos')

' renders the element
Reactos('Reactos', 'Reactos', 'an optional tech label', 'an optional description')
@enduml
```

