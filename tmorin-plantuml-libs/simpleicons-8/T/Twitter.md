# Twitter


```text
simpleicons-8/T/Twitter
```

```text
include('simpleicons-8/T/Twitter')
```



| Illustration | Twitter |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Twitter.png) | ![illustration for Twitter](../../simpleicons-8/T/Twitter.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TwitterXs>`
- `<$TwitterSm>`
- `<$TwitterMd>`
- `<$TwitterLg>`





## Twitter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Twitter
include('simpleicons-8/T/Twitter')

' renders the element
Twitter('Twitter', 'Twitter', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Twitter
include('simpleicons-8/T/Twitter')

' renders the element
Twitter('Twitter', 'Twitter', 'an optional tech label', 'an optional description')
@enduml
```

