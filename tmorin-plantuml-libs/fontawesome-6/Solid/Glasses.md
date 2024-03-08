# Glasses


```text
fontawesome-6/Solid/Glasses
```

```text
include('fontawesome-6/Solid/Glasses')
```



| Illustration | Glasses |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Glasses.png) | ![illustration for Glasses](../../fontawesome-6/Solid/Glasses.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GlassesXs>`
- `<$GlassesSm>`
- `<$GlassesMd>`
- `<$GlassesLg>`





## Glasses

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Glasses
include('fontawesome-6/Solid/Glasses')

' renders the element
Glasses('Glasses', 'Glasses', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Glasses
include('fontawesome-6/Solid/Glasses')

' renders the element
Glasses('Glasses', 'Glasses', 'an optional tech label', 'an optional description')
@enduml
```

