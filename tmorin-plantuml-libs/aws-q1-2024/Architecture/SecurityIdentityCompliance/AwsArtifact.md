# AwsArtifact


```text
aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact
```

```text
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')
```



| Illustration | AwsArtifact | AwsArtifactCard | AwsArtifactGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact.png) | ![illustration for AwsArtifact](../../../aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact.Local.png) | ![illustration for AwsArtifactCard](../../../aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifactCard.Local.png) | ![illustration for AwsArtifactGroup](../../../aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifactGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsArtifactXs>`
- `<$AwsArtifactSm>`
- `<$AwsArtifactMd>`
- `<$AwsArtifactLg>`





## AwsArtifact

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifact
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifact('AwsArtifact', 'Aws Artifact', 'an optional tech label', 'an optional description')
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifact
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifact('AwsArtifact', 'Aws Artifact', 'an optional tech label', 'an optional description')
@enduml
```

## AwsArtifactCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifactCard
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifactCard('AwsArtifactCard', 'Aws Artifact Card', 'an optional description')
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifactCard
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifactCard('AwsArtifactCard', 'Aws Artifact Card', 'an optional description')
@enduml
```

## AwsArtifactGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifactGroup
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifactGroup('AwsArtifactGroup', 'Aws Artifact Group', 'an optional tech label') {
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsArtifactGroup
include('aws-q1-2024/Architecture/SecurityIdentityCompliance/AwsArtifact')

' renders the element
AwsArtifactGroup('AwsArtifactGroup', 'Aws Artifact Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

