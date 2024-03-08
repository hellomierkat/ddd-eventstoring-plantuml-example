# Futurelearn


```text
simpleicons-8/F/Futurelearn
```

```text
include('simpleicons-8/F/Futurelearn')
```



| Illustration | Futurelearn |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Futurelearn.png) | ![illustration for Futurelearn](../../simpleicons-8/F/Futurelearn.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FuturelearnXs>`
- `<$FuturelearnSm>`
- `<$FuturelearnMd>`
- `<$FuturelearnLg>`





## Futurelearn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Futurelearn
include('simpleicons-8/F/Futurelearn')

' renders the element
Futurelearn('Futurelearn', 'Futurelearn', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Futurelearn
include('simpleicons-8/F/Futurelearn')

' renders the element
Futurelearn('Futurelearn', 'Futurelearn', 'an optional tech label', 'an optional description')
@enduml
```

