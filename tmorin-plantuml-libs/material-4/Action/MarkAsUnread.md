# MarkAsUnread


```text
material-4/Action/MarkAsUnread
```

```text
include('material-4/Action/MarkAsUnread')
```



| Illustration | MarkAsUnread |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/MarkAsUnread.png) | ![illustration for MarkAsUnread](../../material-4/Action/MarkAsUnread.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MarkAsUnreadXs>`
- `<$MarkAsUnreadSm>`
- `<$MarkAsUnreadMd>`
- `<$MarkAsUnreadLg>`





## MarkAsUnread

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element MarkAsUnread
include('material-4/Action/MarkAsUnread')

' renders the element
MarkAsUnread('MarkAsUnread', 'Mark As Unread', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element MarkAsUnread
include('material-4/Action/MarkAsUnread')

' renders the element
MarkAsUnread('MarkAsUnread', 'Mark As Unread', 'an optional tech label', 'an optional description')
@enduml
```

