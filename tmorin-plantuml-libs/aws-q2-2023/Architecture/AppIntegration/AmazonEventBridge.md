# AmazonEventBridge


```text
aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge
```

```text
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')
```



| Illustration | AmazonEventBridge | AmazonEventBridgeCard | AmazonEventBridgeGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge.png) | ![illustration for AmazonEventBridge](../../../aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge.Local.png) | ![illustration for AmazonEventBridgeCard](../../../aws-q2-2023/Architecture/AppIntegration/AmazonEventBridgeCard.Local.png) | ![illustration for AmazonEventBridgeGroup](../../../aws-q2-2023/Architecture/AppIntegration/AmazonEventBridgeGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonEventBridgeXs>`
- `<$AmazonEventBridgeSm>`
- `<$AmazonEventBridgeMd>`
- `<$AmazonEventBridgeLg>`





## AmazonEventBridge

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEventBridge
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridge('AmazonEventBridge', 'Amazon Event Bridge', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonEventBridge
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridge('AmazonEventBridge', 'Amazon Event Bridge', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonEventBridgeCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEventBridgeCard
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridgeCard('AmazonEventBridgeCard', 'Amazon Event Bridge Card', 'an optional description')
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

' loads the Item which embeds the element AmazonEventBridgeCard
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridgeCard('AmazonEventBridgeCard', 'Amazon Event Bridge Card', 'an optional description')
@enduml
```

## AmazonEventBridgeGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEventBridgeGroup
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridgeGroup('AmazonEventBridgeGroup', 'Amazon Event Bridge Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonEventBridgeGroup
include('aws-q2-2023/Architecture/AppIntegration/AmazonEventBridge')

' renders the element
AmazonEventBridgeGroup('AmazonEventBridgeGroup', 'Amazon Event Bridge Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

