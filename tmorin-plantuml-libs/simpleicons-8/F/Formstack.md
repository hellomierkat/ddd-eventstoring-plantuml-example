# Formstack


```text
simpleicons-8/F/Formstack
```

```text
include('simpleicons-8/F/Formstack')
```



| Illustration | Formstack |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Formstack.png) | ![illustration for Formstack](../../simpleicons-8/F/Formstack.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FormstackXs>`
- `<$FormstackSm>`
- `<$FormstackMd>`
- `<$FormstackLg>`





## Formstack

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Formstack
include('simpleicons-8/F/Formstack')

' renders the element
Formstack('Formstack', 'Formstack', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Formstack
include('simpleicons-8/F/Formstack')

' renders the element
Formstack('Formstack', 'Formstack', 'an optional tech label', 'an optional description')
@enduml
```

