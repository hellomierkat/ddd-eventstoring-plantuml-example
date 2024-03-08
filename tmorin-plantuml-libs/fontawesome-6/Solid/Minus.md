# Minus


```text
fontawesome-6/Solid/Minus
```

```text
include('fontawesome-6/Solid/Minus')
```



| Illustration | Minus |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Minus.png) | ![illustration for Minus](../../fontawesome-6/Solid/Minus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MinusXs>`
- `<$MinusSm>`
- `<$MinusMd>`
- `<$MinusLg>`





## Minus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Minus
include('fontawesome-6/Solid/Minus')

' renders the element
Minus('Minus', 'Minus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Minus
include('fontawesome-6/Solid/Minus')

' renders the element
Minus('Minus', 'Minus', 'an optional tech label', 'an optional description')
@enduml
```

