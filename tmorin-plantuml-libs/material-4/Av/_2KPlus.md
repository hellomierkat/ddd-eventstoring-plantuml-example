# _2KPlus


```text
material-4/Av/_2KPlus
```

```text
include('material-4/Av/_2KPlus')
```



| Illustration | _2KPlus |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/_2KPlus.png) | ![illustration for _2KPlus](../../material-4/Av/_2KPlus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$_2KPlusXs>`
- `<$_2KPlusSm>`
- `<$_2KPlusMd>`
- `<$_2KPlusLg>`





## _2KPlus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element _2KPlus
include('material-4/Av/_2KPlus')

' renders the element
_2KPlus('2kPlus', '2k Plus', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element _2KPlus
include('material-4/Av/_2KPlus')

' renders the element
_2KPlus('2kPlus', '2k Plus', 'an optional tech label', 'an optional description')
@enduml
```

