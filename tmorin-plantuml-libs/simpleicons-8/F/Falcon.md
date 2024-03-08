# Falcon


```text
simpleicons-8/F/Falcon
```

```text
include('simpleicons-8/F/Falcon')
```



| Illustration | Falcon |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Falcon.png) | ![illustration for Falcon](../../simpleicons-8/F/Falcon.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FalconXs>`
- `<$FalconSm>`
- `<$FalconMd>`
- `<$FalconLg>`





## Falcon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Falcon
include('simpleicons-8/F/Falcon')

' renders the element
Falcon('Falcon', 'Falcon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Falcon
include('simpleicons-8/F/Falcon')

' renders the element
Falcon('Falcon', 'Falcon', 'an optional tech label', 'an optional description')
@enduml
```

