# ForwardFast


```text
fontawesome-6/Solid/ForwardFast
```

```text
include('fontawesome-6/Solid/ForwardFast')
```



| Illustration | ForwardFast |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ForwardFast.png) | ![illustration for ForwardFast](../../fontawesome-6/Solid/ForwardFast.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ForwardFastXs>`
- `<$ForwardFastSm>`
- `<$ForwardFastMd>`
- `<$ForwardFastLg>`





## ForwardFast

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ForwardFast
include('fontawesome-6/Solid/ForwardFast')

' renders the element
ForwardFast('ForwardFast', 'Forward Fast', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ForwardFast
include('fontawesome-6/Solid/ForwardFast')

' renders the element
ForwardFast('ForwardFast', 'Forward Fast', 'an optional tech label', 'an optional description')
@enduml
```

