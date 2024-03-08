# Font


```text
fontawesome-6/Solid/Font
```

```text
include('fontawesome-6/Solid/Font')
```



| Illustration | Font |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Font.png) | ![illustration for Font](../../fontawesome-6/Solid/Font.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FontXs>`
- `<$FontSm>`
- `<$FontMd>`
- `<$FontLg>`





## Font

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Font
include('fontawesome-6/Solid/Font')

' renders the element
Font('Font', 'Font', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Font
include('fontawesome-6/Solid/Font')

' renders the element
Font('Font', 'Font', 'an optional tech label', 'an optional description')
@enduml
```

