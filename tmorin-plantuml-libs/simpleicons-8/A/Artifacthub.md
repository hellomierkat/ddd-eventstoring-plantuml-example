# Artifacthub


```text
simpleicons-8/A/Artifacthub
```

```text
include('simpleicons-8/A/Artifacthub')
```



| Illustration | Artifacthub |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Artifacthub.png) | ![illustration for Artifacthub](../../simpleicons-8/A/Artifacthub.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ArtifacthubXs>`
- `<$ArtifacthubSm>`
- `<$ArtifacthubMd>`
- `<$ArtifacthubLg>`





## Artifacthub

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Artifacthub
include('simpleicons-8/A/Artifacthub')

' renders the element
Artifacthub('Artifacthub', 'Artifacthub', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Artifacthub
include('simpleicons-8/A/Artifacthub')

' renders the element
Artifacthub('Artifacthub', 'Artifacthub', 'an optional tech label', 'an optional description')
@enduml
```

