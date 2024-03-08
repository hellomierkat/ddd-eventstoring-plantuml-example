# Collections


```text
material-4/Image/Collections
```

```text
include('material-4/Image/Collections')
```



| Illustration | Collections |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Collections.png) | ![illustration for Collections](../../material-4/Image/Collections.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CollectionsXs>`
- `<$CollectionsSm>`
- `<$CollectionsMd>`
- `<$CollectionsLg>`





## Collections

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Collections
include('material-4/Image/Collections')

' renders the element
Collections('Collections', 'Collections', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Collections
include('material-4/Image/Collections')

' renders the element
Collections('Collections', 'Collections', 'an optional tech label', 'an optional description')
@enduml
```

