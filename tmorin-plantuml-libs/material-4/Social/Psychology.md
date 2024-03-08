# Psychology


```text
material-4/Social/Psychology
```

```text
include('material-4/Social/Psychology')
```



| Illustration | Psychology |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/Psychology.png) | ![illustration for Psychology](../../material-4/Social/Psychology.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PsychologyXs>`
- `<$PsychologySm>`
- `<$PsychologyMd>`
- `<$PsychologyLg>`





## Psychology

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Psychology
include('material-4/Social/Psychology')

' renders the element
Psychology('Psychology', 'Psychology', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Psychology
include('material-4/Social/Psychology')

' renders the element
Psychology('Psychology', 'Psychology', 'an optional tech label', 'an optional description')
@enduml
```

