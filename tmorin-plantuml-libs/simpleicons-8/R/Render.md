# Render


```text
simpleicons-8/R/Render
```

```text
include('simpleicons-8/R/Render')
```



| Illustration | Render |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Render.png) | ![illustration for Render](../../simpleicons-8/R/Render.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RenderXs>`
- `<$RenderSm>`
- `<$RenderMd>`
- `<$RenderLg>`





## Render

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Render
include('simpleicons-8/R/Render')

' renders the element
Render('Render', 'Render', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Render
include('simpleicons-8/R/Render')

' renders the element
Render('Render', 'Render', 'an optional tech label', 'an optional description')
@enduml
```

