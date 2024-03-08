# Gnometerminal


```text
simpleicons-8/G/Gnometerminal
```

```text
include('simpleicons-8/G/Gnometerminal')
```



| Illustration | Gnometerminal |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gnometerminal.png) | ![illustration for Gnometerminal](../../simpleicons-8/G/Gnometerminal.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GnometerminalXs>`
- `<$GnometerminalSm>`
- `<$GnometerminalMd>`
- `<$GnometerminalLg>`





## Gnometerminal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gnometerminal
include('simpleicons-8/G/Gnometerminal')

' renders the element
Gnometerminal('Gnometerminal', 'Gnometerminal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gnometerminal
include('simpleicons-8/G/Gnometerminal')

' renders the element
Gnometerminal('Gnometerminal', 'Gnometerminal', 'an optional tech label', 'an optional description')
@enduml
```

