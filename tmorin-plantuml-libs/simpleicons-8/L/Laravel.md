# Laravel


```text
simpleicons-8/L/Laravel
```

```text
include('simpleicons-8/L/Laravel')
```



| Illustration | Laravel |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Laravel.png) | ![illustration for Laravel](../../simpleicons-8/L/Laravel.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LaravelXs>`
- `<$LaravelSm>`
- `<$LaravelMd>`
- `<$LaravelLg>`





## Laravel

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Laravel
include('simpleicons-8/L/Laravel')

' renders the element
Laravel('Laravel', 'Laravel', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Laravel
include('simpleicons-8/L/Laravel')

' renders the element
Laravel('Laravel', 'Laravel', 'an optional tech label', 'an optional description')
@enduml
```

