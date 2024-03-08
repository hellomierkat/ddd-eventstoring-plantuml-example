# FilePresent


```text
material-4/Action/FilePresent
```

```text
include('material-4/Action/FilePresent')
```



| Illustration | FilePresent |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/FilePresent.png) | ![illustration for FilePresent](../../material-4/Action/FilePresent.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FilePresentXs>`
- `<$FilePresentSm>`
- `<$FilePresentMd>`
- `<$FilePresentLg>`





## FilePresent

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FilePresent
include('material-4/Action/FilePresent')

' renders the element
FilePresent('FilePresent', 'File Present', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FilePresent
include('material-4/Action/FilePresent')

' renders the element
FilePresent('FilePresent', 'File Present', 'an optional tech label', 'an optional description')
@enduml
```

