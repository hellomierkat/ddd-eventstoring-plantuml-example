# Suzuki


```text
simpleicons-8/S/Suzuki
```

```text
include('simpleicons-8/S/Suzuki')
```



| Illustration | Suzuki |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Suzuki.png) | ![illustration for Suzuki](../../simpleicons-8/S/Suzuki.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SuzukiXs>`
- `<$SuzukiSm>`
- `<$SuzukiMd>`
- `<$SuzukiLg>`





## Suzuki

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Suzuki
include('simpleicons-8/S/Suzuki')

' renders the element
Suzuki('Suzuki', 'Suzuki', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Suzuki
include('simpleicons-8/S/Suzuki')

' renders the element
Suzuki('Suzuki', 'Suzuki', 'an optional tech label', 'an optional description')
@enduml
```

