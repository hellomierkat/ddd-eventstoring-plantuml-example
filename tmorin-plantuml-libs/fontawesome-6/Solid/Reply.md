# Reply


```text
fontawesome-6/Solid/Reply
```

```text
include('fontawesome-6/Solid/Reply')
```



| Illustration | Reply |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Reply.png) | ![illustration for Reply](../../fontawesome-6/Solid/Reply.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReplyXs>`
- `<$ReplySm>`
- `<$ReplyMd>`
- `<$ReplyLg>`





## Reply

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Reply
include('fontawesome-6/Solid/Reply')

' renders the element
Reply('Reply', 'Reply', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reply
include('fontawesome-6/Solid/Reply')

' renders the element
Reply('Reply', 'Reply', 'an optional tech label', 'an optional description')
@enduml
```

