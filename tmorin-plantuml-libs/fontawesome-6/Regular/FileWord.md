# FileWord


```text
fontawesome-6/Regular/FileWord
```

```text
include('fontawesome-6/Regular/FileWord')
```



| Illustration | FileWord |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/FileWord.png) | ![illustration for FileWord](../../fontawesome-6/Regular/FileWord.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FileWordXs>`
- `<$FileWordSm>`
- `<$FileWordMd>`
- `<$FileWordLg>`





## FileWord

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FileWord
include('fontawesome-6/Regular/FileWord')

' renders the element
FileWord('FileWord', 'File Word', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FileWord
include('fontawesome-6/Regular/FileWord')

' renders the element
FileWord('FileWord', 'File Word', 'an optional tech label', 'an optional description')
@enduml
```

