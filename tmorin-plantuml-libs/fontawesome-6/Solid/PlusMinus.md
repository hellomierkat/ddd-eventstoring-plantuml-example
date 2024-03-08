# PlusMinus


```text
fontawesome-6/Solid/PlusMinus
```

```text
include('fontawesome-6/Solid/PlusMinus')
```



| Illustration | PlusMinus |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PlusMinus.png) | ![illustration for PlusMinus](../../fontawesome-6/Solid/PlusMinus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PlusMinusXs>`
- `<$PlusMinusSm>`
- `<$PlusMinusMd>`
- `<$PlusMinusLg>`





## PlusMinus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PlusMinus
include('fontawesome-6/Solid/PlusMinus')

' renders the element
PlusMinus('PlusMinus', 'Plus Minus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PlusMinus
include('fontawesome-6/Solid/PlusMinus')

' renders the element
PlusMinus('PlusMinus', 'Plus Minus', 'an optional tech label', 'an optional description')
@enduml
```

