# Emirates


```text
simpleicons-8/E/Emirates
```

```text
include('simpleicons-8/E/Emirates')
```



| Illustration | Emirates |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/E/Emirates.png) | ![illustration for Emirates](../../simpleicons-8/E/Emirates.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EmiratesXs>`
- `<$EmiratesSm>`
- `<$EmiratesMd>`
- `<$EmiratesLg>`





## Emirates

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Emirates
include('simpleicons-8/E/Emirates')

' renders the element
Emirates('Emirates', 'Emirates', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Emirates
include('simpleicons-8/E/Emirates')

' renders the element
Emirates('Emirates', 'Emirates', 'an optional tech label', 'an optional description')
@enduml
```

