# Micropython


```text
simpleicons-8/M/Micropython
```

```text
include('simpleicons-8/M/Micropython')
```



| Illustration | Micropython |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Micropython.png) | ![illustration for Micropython](../../simpleicons-8/M/Micropython.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MicropythonXs>`
- `<$MicropythonSm>`
- `<$MicropythonMd>`
- `<$MicropythonLg>`





## Micropython

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Micropython
include('simpleicons-8/M/Micropython')

' renders the element
Micropython('Micropython', 'Micropython', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Micropython
include('simpleicons-8/M/Micropython')

' renders the element
Micropython('Micropython', 'Micropython', 'an optional tech label', 'an optional description')
@enduml
```

