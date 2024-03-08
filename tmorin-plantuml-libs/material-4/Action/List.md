# List


```text
material-4/Action/List
```

```text
include('material-4/Action/List')
```



| Illustration | List |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/List.png) | ![illustration for List](../../material-4/Action/List.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ListXs>`
- `<$ListSm>`
- `<$ListMd>`
- `<$ListLg>`





## List

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element List
include('material-4/Action/List')

' renders the element
List('List', 'List', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element List
include('material-4/Action/List')

' renders the element
List('List', 'List', 'an optional tech label', 'an optional description')
@enduml
```

