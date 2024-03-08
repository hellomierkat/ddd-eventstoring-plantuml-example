# TrackChanges


```text
material-4/Action/TrackChanges
```

```text
include('material-4/Action/TrackChanges')
```



| Illustration | TrackChanges |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/TrackChanges.png) | ![illustration for TrackChanges](../../material-4/Action/TrackChanges.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TrackChangesXs>`
- `<$TrackChangesSm>`
- `<$TrackChangesMd>`
- `<$TrackChangesLg>`





## TrackChanges

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element TrackChanges
include('material-4/Action/TrackChanges')

' renders the element
TrackChanges('TrackChanges', 'Track Changes', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TrackChanges
include('material-4/Action/TrackChanges')

' renders the element
TrackChanges('TrackChanges', 'Track Changes', 'an optional tech label', 'an optional description')
@enduml
```

