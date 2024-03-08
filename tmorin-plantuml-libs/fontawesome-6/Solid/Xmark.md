# Xmark


```text
fontawesome-6/Solid/Xmark
```

```text
include('fontawesome-6/Solid/Xmark')
```



| Illustration | Xmark |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Xmark.png) | ![illustration for Xmark](../../fontawesome-6/Solid/Xmark.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$XmarkXs>`
- `<$XmarkSm>`
- `<$XmarkMd>`
- `<$XmarkLg>`





## Xmark

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Xmark
include('fontawesome-6/Solid/Xmark')

' renders the element
Xmark('Xmark', 'Xmark', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Xmark
include('fontawesome-6/Solid/Xmark')

' renders the element
Xmark('Xmark', 'Xmark', 'an optional tech label', 'an optional description')
@enduml
```

