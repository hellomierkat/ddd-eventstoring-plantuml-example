# Statamic


```text
simpleicons-8/S/Statamic
```

```text
include('simpleicons-8/S/Statamic')
```



| Illustration | Statamic |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Statamic.png) | ![illustration for Statamic](../../simpleicons-8/S/Statamic.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$StatamicXs>`
- `<$StatamicSm>`
- `<$StatamicMd>`
- `<$StatamicLg>`





## Statamic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Statamic
include('simpleicons-8/S/Statamic')

' renders the element
Statamic('Statamic', 'Statamic', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Statamic
include('simpleicons-8/S/Statamic')

' renders the element
Statamic('Statamic', 'Statamic', 'an optional tech label', 'an optional description')
@enduml
```

