# Assistant


```text
material-4/Image/Assistant
```

```text
include('material-4/Image/Assistant')
```



| Illustration | Assistant |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Assistant.png) | ![illustration for Assistant](../../material-4/Image/Assistant.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AssistantXs>`
- `<$AssistantSm>`
- `<$AssistantMd>`
- `<$AssistantLg>`





## Assistant

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Assistant
include('material-4/Image/Assistant')

' renders the element
Assistant('Assistant', 'Assistant', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Assistant
include('material-4/Image/Assistant')

' renders the element
Assistant('Assistant', 'Assistant', 'an optional tech label', 'an optional description')
@enduml
```

