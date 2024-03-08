# Poll


```text
material-4/Social/Poll
```

```text
include('material-4/Social/Poll')
```



| Illustration | Poll |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/Poll.png) | ![illustration for Poll](../../material-4/Social/Poll.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PollXs>`
- `<$PollSm>`
- `<$PollMd>`
- `<$PollLg>`





## Poll

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Poll
include('material-4/Social/Poll')

' renders the element
Poll('Poll', 'Poll', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Poll
include('material-4/Social/Poll')

' renders the element
Poll('Poll', 'Poll', 'an optional tech label', 'an optional description')
@enduml
```

