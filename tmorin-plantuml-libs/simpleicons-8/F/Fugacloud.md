# Fugacloud


```text
simpleicons-8/F/Fugacloud
```

```text
include('simpleicons-8/F/Fugacloud')
```



| Illustration | Fugacloud |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Fugacloud.png) | ![illustration for Fugacloud](../../simpleicons-8/F/Fugacloud.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FugacloudXs>`
- `<$FugacloudSm>`
- `<$FugacloudMd>`
- `<$FugacloudLg>`





## Fugacloud

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Fugacloud
include('simpleicons-8/F/Fugacloud')

' renders the element
Fugacloud('Fugacloud', 'Fugacloud', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fugacloud
include('simpleicons-8/F/Fugacloud')

' renders the element
Fugacloud('Fugacloud', 'Fugacloud', 'an optional tech label', 'an optional description')
@enduml
```

