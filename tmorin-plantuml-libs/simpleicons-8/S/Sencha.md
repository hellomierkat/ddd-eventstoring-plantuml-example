# Sencha


```text
simpleicons-8/S/Sencha
```

```text
include('simpleicons-8/S/Sencha')
```



| Illustration | Sencha |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Sencha.png) | ![illustration for Sencha](../../simpleicons-8/S/Sencha.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SenchaXs>`
- `<$SenchaSm>`
- `<$SenchaMd>`
- `<$SenchaLg>`





## Sencha

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Sencha
include('simpleicons-8/S/Sencha')

' renders the element
Sencha('Sencha', 'Sencha', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sencha
include('simpleicons-8/S/Sencha')

' renders the element
Sencha('Sencha', 'Sencha', 'an optional tech label', 'an optional description')
@enduml
```

