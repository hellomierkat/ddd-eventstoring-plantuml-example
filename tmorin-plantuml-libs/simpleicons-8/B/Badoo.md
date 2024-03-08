# Badoo


```text
simpleicons-8/B/Badoo
```

```text
include('simpleicons-8/B/Badoo')
```



| Illustration | Badoo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Badoo.png) | ![illustration for Badoo](../../simpleicons-8/B/Badoo.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BadooXs>`
- `<$BadooSm>`
- `<$BadooMd>`
- `<$BadooLg>`





## Badoo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Badoo
include('simpleicons-8/B/Badoo')

' renders the element
Badoo('Badoo', 'Badoo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Badoo
include('simpleicons-8/B/Badoo')

' renders the element
Badoo('Badoo', 'Badoo', 'an optional tech label', 'an optional description')
@enduml
```

