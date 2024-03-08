# Retweet


```text
fontawesome-6/Solid/Retweet
```

```text
include('fontawesome-6/Solid/Retweet')
```



| Illustration | Retweet |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Retweet.png) | ![illustration for Retweet](../../fontawesome-6/Solid/Retweet.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RetweetXs>`
- `<$RetweetSm>`
- `<$RetweetMd>`
- `<$RetweetLg>`





## Retweet

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Retweet
include('fontawesome-6/Solid/Retweet')

' renders the element
Retweet('Retweet', 'Retweet', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Retweet
include('fontawesome-6/Solid/Retweet')

' renders the element
Retweet('Retweet', 'Retweet', 'an optional tech label', 'an optional description')
@enduml
```

