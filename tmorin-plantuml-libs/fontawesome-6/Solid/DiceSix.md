# DiceSix


```text
fontawesome-6/Solid/DiceSix
```

```text
include('fontawesome-6/Solid/DiceSix')
```



| Illustration | DiceSix |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/DiceSix.png) | ![illustration for DiceSix](../../fontawesome-6/Solid/DiceSix.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DiceSixXs>`
- `<$DiceSixSm>`
- `<$DiceSixMd>`
- `<$DiceSixLg>`





## DiceSix

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element DiceSix
include('fontawesome-6/Solid/DiceSix')

' renders the element
DiceSix('DiceSix', 'Dice Six', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element DiceSix
include('fontawesome-6/Solid/DiceSix')

' renders the element
DiceSix('DiceSix', 'Dice Six', 'an optional tech label', 'an optional description')
@enduml
```

