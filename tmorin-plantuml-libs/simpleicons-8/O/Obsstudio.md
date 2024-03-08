# Obsstudio


```text
simpleicons-8/O/Obsstudio
```

```text
include('simpleicons-8/O/Obsstudio')
```



| Illustration | Obsstudio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/O/Obsstudio.png) | ![illustration for Obsstudio](../../simpleicons-8/O/Obsstudio.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ObsstudioXs>`
- `<$ObsstudioSm>`
- `<$ObsstudioMd>`
- `<$ObsstudioLg>`





## Obsstudio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Obsstudio
include('simpleicons-8/O/Obsstudio')

' renders the element
Obsstudio('Obsstudio', 'Obsstudio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Obsstudio
include('simpleicons-8/O/Obsstudio')

' renders the element
Obsstudio('Obsstudio', 'Obsstudio', 'an optional tech label', 'an optional description')
@enduml
```

