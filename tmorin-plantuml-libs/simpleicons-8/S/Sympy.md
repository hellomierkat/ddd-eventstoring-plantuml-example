# Sympy


```text
simpleicons-8/S/Sympy
```

```text
include('simpleicons-8/S/Sympy')
```



| Illustration | Sympy |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Sympy.png) | ![illustration for Sympy](../../simpleicons-8/S/Sympy.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SympyXs>`
- `<$SympySm>`
- `<$SympyMd>`
- `<$SympyLg>`





## Sympy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Sympy
include('simpleicons-8/S/Sympy')

' renders the element
Sympy('Sympy', 'Sympy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sympy
include('simpleicons-8/S/Sympy')

' renders the element
Sympy('Sympy', 'Sympy', 'an optional tech label', 'an optional description')
@enduml
```

