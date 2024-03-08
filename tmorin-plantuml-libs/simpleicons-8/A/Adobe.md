# Adobe


```text
simpleicons-8/A/Adobe
```

```text
include('simpleicons-8/A/Adobe')
```



| Illustration | Adobe |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Adobe.png) | ![illustration for Adobe](../../simpleicons-8/A/Adobe.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AdobeXs>`
- `<$AdobeSm>`
- `<$AdobeMd>`
- `<$AdobeLg>`





## Adobe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Adobe
include('simpleicons-8/A/Adobe')

' renders the element
Adobe('Adobe', 'Adobe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Adobe
include('simpleicons-8/A/Adobe')

' renders the element
Adobe('Adobe', 'Adobe', 'an optional tech label', 'an optional description')
@enduml
```

