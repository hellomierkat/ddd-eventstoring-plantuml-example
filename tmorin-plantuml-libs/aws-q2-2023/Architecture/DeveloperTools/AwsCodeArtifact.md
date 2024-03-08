# AwsCodeArtifact


```text
aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact
```

```text
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')
```



| Illustration | AwsCodeArtifact | AwsCodeArtifactCard | AwsCodeArtifactGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact.png) | ![illustration for AwsCodeArtifact](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact.Local.png) | ![illustration for AwsCodeArtifactCard](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifactCard.Local.png) | ![illustration for AwsCodeArtifactGroup](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifactGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsCodeArtifactXs>`
- `<$AwsCodeArtifactSm>`
- `<$AwsCodeArtifactMd>`
- `<$AwsCodeArtifactLg>`





## AwsCodeArtifact

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifact
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifact('AwsCodeArtifact', 'Aws Code Artifact', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifact
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifact('AwsCodeArtifact', 'Aws Code Artifact', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCodeArtifactCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifactCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifactCard('AwsCodeArtifactCard', 'Aws Code Artifact Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifactCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifactCard('AwsCodeArtifactCard', 'Aws Code Artifact Card', 'an optional description')
@enduml
```

## AwsCodeArtifactGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifactGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifactGroup('AwsCodeArtifactGroup', 'Aws Code Artifact Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeArtifactGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeArtifact')

' renders the element
AwsCodeArtifactGroup('AwsCodeArtifactGroup', 'Aws Code Artifact Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

