# Mobile


```text
fontawesome-6/Solid/Mobile
```

```text
include('fontawesome-6/Solid/Mobile')
```



| Illustration | Mobile |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Mobile.png) | ![illustration for Mobile](../../fontawesome-6/Solid/Mobile.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MobileXs>`
- `<$MobileSm>`
- `<$MobileMd>`
- `<$MobileLg>`





## Mobile

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Mobile
include('fontawesome-6/Solid/Mobile')

' renders the element
Mobile('Mobile', 'Mobile', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mobile
include('fontawesome-6/Solid/Mobile')

' renders the element
Mobile('Mobile', 'Mobile', 'an optional tech label', 'an optional description')
@enduml
```

