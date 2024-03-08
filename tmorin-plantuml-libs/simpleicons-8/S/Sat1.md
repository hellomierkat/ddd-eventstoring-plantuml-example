# Sat1


```text
simpleicons-8/S/Sat1
```

```text
include('simpleicons-8/S/Sat1')
```



| Illustration | Sat1 |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Sat1.png) | ![illustration for Sat1](../../simpleicons-8/S/Sat1.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Sat1Xs>`
- `<$Sat1Sm>`
- `<$Sat1Md>`
- `<$Sat1Lg>`





## Sat1

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Sat1
include('simpleicons-8/S/Sat1')

' renders the element
Sat1('Sat1', 'Sat1', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sat1
include('simpleicons-8/S/Sat1')

' renders the element
Sat1('Sat1', 'Sat1', 'an optional tech label', 'an optional description')
@enduml
```

