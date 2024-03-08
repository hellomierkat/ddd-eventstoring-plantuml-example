# Ballot


```text
material-4/Content/Ballot
```

```text
include('material-4/Content/Ballot')
```



| Illustration | Ballot |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Ballot.png) | ![illustration for Ballot](../../material-4/Content/Ballot.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BallotXs>`
- `<$BallotSm>`
- `<$BallotMd>`
- `<$BallotLg>`





## Ballot

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Ballot
include('material-4/Content/Ballot')

' renders the element
Ballot('Ballot', 'Ballot', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ballot
include('material-4/Content/Ballot')

' renders the element
Ballot('Ballot', 'Ballot', 'an optional tech label', 'an optional description')
@enduml
```

