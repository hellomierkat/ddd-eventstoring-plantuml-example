# AmazonInspectorAgent


```text
aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent
```

```text
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')
```



| Illustration | AmazonInspectorAgent | AmazonInspectorAgentCard | AmazonInspectorAgentGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent.png) | ![illustration for AmazonInspectorAgent](../../../aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent.Local.png) | ![illustration for AmazonInspectorAgentCard](../../../aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgentCard.Local.png) | ![illustration for AmazonInspectorAgentGroup](../../../aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgentGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonInspectorAgentXs>`
- `<$AmazonInspectorAgentSm>`
- `<$AmazonInspectorAgentMd>`
- `<$AmazonInspectorAgentLg>`





## AmazonInspectorAgent

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonInspectorAgent
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgent('AmazonInspectorAgent', 'Amazon Inspector Agent', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonInspectorAgent
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgent('AmazonInspectorAgent', 'Amazon Inspector Agent', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonInspectorAgentCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonInspectorAgentCard
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgentCard('AmazonInspectorAgentCard', 'Amazon Inspector Agent Card', 'an optional description')
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

' loads the Item which embeds the element AmazonInspectorAgentCard
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgentCard('AmazonInspectorAgentCard', 'Amazon Inspector Agent Card', 'an optional description')
@enduml
```

## AmazonInspectorAgentGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonInspectorAgentGroup
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgentGroup('AmazonInspectorAgentGroup', 'Amazon Inspector Agent Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonInspectorAgentGroup
include('aws-q1-2024/Resource/SecurityIdentityCompliance/AmazonInspectorAgent')

' renders the element
AmazonInspectorAgentGroup('AmazonInspectorAgentGroup', 'Amazon Inspector Agent Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

