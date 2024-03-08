# SimCard


```text
material-4/Hardware/SimCard
```

```text
include('material-4/Hardware/SimCard')
```



| Illustration | SimCard |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Hardware/SimCard.png) | ![illustration for SimCard](../../material-4/Hardware/SimCard.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SimCardXs>`
- `<$SimCardSm>`
- `<$SimCardMd>`
- `<$SimCardLg>`





## SimCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SimCard
include('material-4/Hardware/SimCard')

' renders the element
SimCard('SimCard', 'Sim Card', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SimCard
include('material-4/Hardware/SimCard')

' renders the element
SimCard('SimCard', 'Sim Card', 'an optional tech label', 'an optional description')
@enduml
```

