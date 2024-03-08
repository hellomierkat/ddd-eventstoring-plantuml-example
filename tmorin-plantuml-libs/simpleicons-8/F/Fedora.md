# Fedora


```text
simpleicons-8/F/Fedora
```

```text
include('simpleicons-8/F/Fedora')
```



| Illustration | Fedora |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Fedora.png) | ![illustration for Fedora](../../simpleicons-8/F/Fedora.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FedoraXs>`
- `<$FedoraSm>`
- `<$FedoraMd>`
- `<$FedoraLg>`





## Fedora

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Fedora
include('simpleicons-8/F/Fedora')

' renders the element
Fedora('Fedora', 'Fedora', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fedora
include('simpleicons-8/F/Fedora')

' renders the element
Fedora('Fedora', 'Fedora', 'an optional tech label', 'an optional description')
@enduml
```

