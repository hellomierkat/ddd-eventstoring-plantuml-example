# Cryengine


```text
simpleicons-8/C/Cryengine
```

```text
include('simpleicons-8/C/Cryengine')
```



| Illustration | Cryengine |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Cryengine.png) | ![illustration for Cryengine](../../simpleicons-8/C/Cryengine.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CryengineXs>`
- `<$CryengineSm>`
- `<$CryengineMd>`
- `<$CryengineLg>`





## Cryengine

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Cryengine
include('simpleicons-8/C/Cryengine')

' renders the element
Cryengine('Cryengine', 'Cryengine', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cryengine
include('simpleicons-8/C/Cryengine')

' renders the element
Cryengine('Cryengine', 'Cryengine', 'an optional tech label', 'an optional description')
@enduml
```

