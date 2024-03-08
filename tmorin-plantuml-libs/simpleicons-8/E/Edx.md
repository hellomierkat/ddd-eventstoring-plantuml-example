# Edx


```text
simpleicons-8/E/Edx
```

```text
include('simpleicons-8/E/Edx')
```



| Illustration | Edx |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/E/Edx.png) | ![illustration for Edx](../../simpleicons-8/E/Edx.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EdxXs>`
- `<$EdxSm>`
- `<$EdxMd>`
- `<$EdxLg>`





## Edx

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Edx
include('simpleicons-8/E/Edx')

' renders the element
Edx('Edx', 'Edx', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Edx
include('simpleicons-8/E/Edx')

' renders the element
Edx('Edx', 'Edx', 'an optional tech label', 'an optional description')
@enduml
```

