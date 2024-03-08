# FileExcel


```text
fontawesome-6/Regular/FileExcel
```

```text
include('fontawesome-6/Regular/FileExcel')
```



| Illustration | FileExcel |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/FileExcel.png) | ![illustration for FileExcel](../../fontawesome-6/Regular/FileExcel.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FileExcelXs>`
- `<$FileExcelSm>`
- `<$FileExcelMd>`
- `<$FileExcelLg>`





## FileExcel

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FileExcel
include('fontawesome-6/Regular/FileExcel')

' renders the element
FileExcel('FileExcel', 'File Excel', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FileExcel
include('fontawesome-6/Regular/FileExcel')

' renders the element
FileExcel('FileExcel', 'File Excel', 'an optional tech label', 'an optional description')
@enduml
```

