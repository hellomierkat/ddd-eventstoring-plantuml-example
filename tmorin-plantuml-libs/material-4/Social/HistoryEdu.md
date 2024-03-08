# HistoryEdu


```text
material-4/Social/HistoryEdu
```

```text
include('material-4/Social/HistoryEdu')
```



| Illustration | HistoryEdu |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/HistoryEdu.png) | ![illustration for HistoryEdu](../../material-4/Social/HistoryEdu.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HistoryEduXs>`
- `<$HistoryEduSm>`
- `<$HistoryEduMd>`
- `<$HistoryEduLg>`





## HistoryEdu

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element HistoryEdu
include('material-4/Social/HistoryEdu')

' renders the element
HistoryEdu('HistoryEdu', 'History Edu', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HistoryEdu
include('material-4/Social/HistoryEdu')

' renders the element
HistoryEdu('HistoryEdu', 'History Edu', 'an optional tech label', 'an optional description')
@enduml
```

