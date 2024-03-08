# TableRows


```text
material-4/Editor/TableRows
```

```text
include('material-4/Editor/TableRows')
```



| Illustration | TableRows |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/TableRows.png) | ![illustration for TableRows](../../material-4/Editor/TableRows.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TableRowsXs>`
- `<$TableRowsSm>`
- `<$TableRowsMd>`
- `<$TableRowsLg>`





## TableRows

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element TableRows
include('material-4/Editor/TableRows')

' renders the element
TableRows('TableRows', 'Table Rows', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TableRows
include('material-4/Editor/TableRows')

' renders the element
TableRows('TableRows', 'Table Rows', 'an optional tech label', 'an optional description')
@enduml
```

