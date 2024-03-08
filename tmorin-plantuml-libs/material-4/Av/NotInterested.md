# NotInterested


```text
material-4/Av/NotInterested
```

```text
include('material-4/Av/NotInterested')
```



| Illustration | NotInterested |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/NotInterested.png) | ![illustration for NotInterested](../../material-4/Av/NotInterested.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$NotInterestedXs>`
- `<$NotInterestedSm>`
- `<$NotInterestedMd>`
- `<$NotInterestedLg>`





## NotInterested

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element NotInterested
include('material-4/Av/NotInterested')

' renders the element
NotInterested('NotInterested', 'Not Interested', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element NotInterested
include('material-4/Av/NotInterested')

' renders the element
NotInterested('NotInterested', 'Not Interested', 'an optional tech label', 'an optional description')
@enduml
```

