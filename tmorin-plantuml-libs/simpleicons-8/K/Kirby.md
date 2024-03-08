# Kirby


```text
simpleicons-8/K/Kirby
```

```text
include('simpleicons-8/K/Kirby')
```



| Illustration | Kirby |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/K/Kirby.png) | ![illustration for Kirby](../../simpleicons-8/K/Kirby.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KirbyXs>`
- `<$KirbySm>`
- `<$KirbyMd>`
- `<$KirbyLg>`





## Kirby

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Kirby
include('simpleicons-8/K/Kirby')

' renders the element
Kirby('Kirby', 'Kirby', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Kirby
include('simpleicons-8/K/Kirby')

' renders the element
Kirby('Kirby', 'Kirby', 'an optional tech label', 'an optional description')
@enduml
```

