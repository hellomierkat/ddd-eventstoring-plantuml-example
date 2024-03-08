# Houzz


```text
simpleicons-8/H/Houzz
```

```text
include('simpleicons-8/H/Houzz')
```



| Illustration | Houzz |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/H/Houzz.png) | ![illustration for Houzz](../../simpleicons-8/H/Houzz.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HouzzXs>`
- `<$HouzzSm>`
- `<$HouzzMd>`
- `<$HouzzLg>`





## Houzz

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Houzz
include('simpleicons-8/H/Houzz')

' renders the element
Houzz('Houzz', 'Houzz', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Houzz
include('simpleicons-8/H/Houzz')

' renders the element
Houzz('Houzz', 'Houzz', 'an optional tech label', 'an optional description')
@enduml
```

