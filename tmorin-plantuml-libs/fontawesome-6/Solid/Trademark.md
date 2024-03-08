# Trademark


```text
fontawesome-6/Solid/Trademark
```

```text
include('fontawesome-6/Solid/Trademark')
```



| Illustration | Trademark |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Trademark.png) | ![illustration for Trademark](../../fontawesome-6/Solid/Trademark.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TrademarkXs>`
- `<$TrademarkSm>`
- `<$TrademarkMd>`
- `<$TrademarkLg>`





## Trademark

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Trademark
include('fontawesome-6/Solid/Trademark')

' renders the element
Trademark('Trademark', 'Trademark', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Trademark
include('fontawesome-6/Solid/Trademark')

' renders the element
Trademark('Trademark', 'Trademark', 'an optional tech label', 'an optional description')
@enduml
```

