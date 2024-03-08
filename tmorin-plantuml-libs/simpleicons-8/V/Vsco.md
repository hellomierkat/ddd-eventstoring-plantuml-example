# Vsco


```text
simpleicons-8/V/Vsco
```

```text
include('simpleicons-8/V/Vsco')
```



| Illustration | Vsco |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/V/Vsco.png) | ![illustration for Vsco](../../simpleicons-8/V/Vsco.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VscoXs>`
- `<$VscoSm>`
- `<$VscoMd>`
- `<$VscoLg>`





## Vsco

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Vsco
include('simpleicons-8/V/Vsco')

' renders the element
Vsco('Vsco', 'Vsco', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vsco
include('simpleicons-8/V/Vsco')

' renders the element
Vsco('Vsco', 'Vsco', 'an optional tech label', 'an optional description')
@enduml
```

