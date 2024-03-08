# AmazonApiGateway


```text
aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway
```

```text
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')
```



| Illustration | AmazonApiGateway | AmazonApiGatewayCard | AmazonApiGatewayGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway.png) | ![illustration for AmazonApiGateway](../../../aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway.Local.png) | ![illustration for AmazonApiGatewayCard](../../../aws-q1-2024/Architecture/AppIntegration/AmazonApiGatewayCard.Local.png) | ![illustration for AmazonApiGatewayGroup](../../../aws-q1-2024/Architecture/AppIntegration/AmazonApiGatewayGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonApiGatewayXs>`
- `<$AmazonApiGatewaySm>`
- `<$AmazonApiGatewayMd>`
- `<$AmazonApiGatewayLg>`





## AmazonApiGateway

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonApiGateway
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGateway('AmazonApiGateway', 'Amazon Api Gateway', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonApiGateway
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGateway('AmazonApiGateway', 'Amazon Api Gateway', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonApiGatewayCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonApiGatewayCard
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGatewayCard('AmazonApiGatewayCard', 'Amazon Api Gateway Card', 'an optional description')
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

' loads the Item which embeds the element AmazonApiGatewayCard
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGatewayCard('AmazonApiGatewayCard', 'Amazon Api Gateway Card', 'an optional description')
@enduml
```

## AmazonApiGatewayGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonApiGatewayGroup
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGatewayGroup('AmazonApiGatewayGroup', 'Amazon Api Gateway Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonApiGatewayGroup
include('aws-q1-2024/Architecture/AppIntegration/AmazonApiGateway')

' renders the element
AmazonApiGatewayGroup('AmazonApiGatewayGroup', 'Amazon Api Gateway Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

