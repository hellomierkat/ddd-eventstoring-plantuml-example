# AwsDirectConnectGateway


```text
aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway
```

```text
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')
```



| Illustration | AwsDirectConnectGateway | AwsDirectConnectGatewayCard | AwsDirectConnectGatewayGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway.png) | ![illustration for AwsDirectConnectGateway](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway.Local.png) | ![illustration for AwsDirectConnectGatewayCard](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGatewayCard.Local.png) | ![illustration for AwsDirectConnectGatewayGroup](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGatewayGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsDirectConnectGatewayXs>`
- `<$AwsDirectConnectGatewaySm>`
- `<$AwsDirectConnectGatewayMd>`
- `<$AwsDirectConnectGatewayLg>`





## AwsDirectConnectGateway

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsDirectConnectGateway
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGateway('AwsDirectConnectGateway', 'Aws Direct Connect Gateway', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsDirectConnectGateway
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGateway('AwsDirectConnectGateway', 'Aws Direct Connect Gateway', 'an optional tech label', 'an optional description')
@enduml
```

## AwsDirectConnectGatewayCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsDirectConnectGatewayCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGatewayCard('AwsDirectConnectGatewayCard', 'Aws Direct Connect Gateway Card', 'an optional description')
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

' loads the Item which embeds the element AwsDirectConnectGatewayCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGatewayCard('AwsDirectConnectGatewayCard', 'Aws Direct Connect Gateway Card', 'an optional description')
@enduml
```

## AwsDirectConnectGatewayGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsDirectConnectGatewayGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGatewayGroup('AwsDirectConnectGatewayGroup', 'Aws Direct Connect Gateway Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsDirectConnectGatewayGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsDirectConnectGateway')

' renders the element
AwsDirectConnectGatewayGroup('AwsDirectConnectGatewayGroup', 'Aws Direct Connect Gateway Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

