# Blazor


```text
simpleicons-8/B/Blazor
```

```text
include('simpleicons-8/B/Blazor')
```



| Illustration | Blazor |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/B/Blazor.png) | ![illustration for Blazor](../../simpleicons-8/B/Blazor.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BlazorXs>`
- `<$BlazorSm>`
- `<$BlazorMd>`
- `<$BlazorLg>`





## Blazor

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Blazor
include('simpleicons-8/B/Blazor')

' renders the element
Blazor('Blazor', 'Blazor', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Blazor
include('simpleicons-8/B/Blazor')

' renders the element
Blazor('Blazor', 'Blazor', 'an optional tech label', 'an optional description')
@enduml
```

