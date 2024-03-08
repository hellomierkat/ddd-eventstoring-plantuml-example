# ServiceAzureDataboxGateway


```text
azure-17/Item/Integration/ServiceAzureDataboxGateway
```

```text
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')
```



| Illustration | ServiceAzureDataboxGateway | ServiceAzureDataboxGatewayCard | ServiceAzureDataboxGatewayGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Integration/ServiceAzureDataboxGateway.png) | ![illustration for ServiceAzureDataboxGateway](../../../azure-17/Item/Integration/ServiceAzureDataboxGateway.Local.png) | ![illustration for ServiceAzureDataboxGatewayCard](../../../azure-17/Item/Integration/ServiceAzureDataboxGatewayCard.Local.png) | ![illustration for ServiceAzureDataboxGatewayGroup](../../../azure-17/Item/Integration/ServiceAzureDataboxGatewayGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAzureDataboxGatewayXs>`
- `<$ServiceAzureDataboxGatewaySm>`
- `<$ServiceAzureDataboxGatewayMd>`
- `<$ServiceAzureDataboxGatewayLg>`





## ServiceAzureDataboxGateway

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGateway
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGateway('ServiceAzureDataboxGateway', 'Service Azure Databox Gateway', 'an optional tech label', 'an optional description')
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGateway
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGateway('ServiceAzureDataboxGateway', 'Service Azure Databox Gateway', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAzureDataboxGatewayCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGatewayCard
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGatewayCard('ServiceAzureDataboxGatewayCard', 'Service Azure Databox Gateway Card', 'an optional description')
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGatewayCard
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGatewayCard('ServiceAzureDataboxGatewayCard', 'Service Azure Databox Gateway Card', 'an optional description')
@enduml
```

## ServiceAzureDataboxGatewayGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGatewayGroup
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGatewayGroup('ServiceAzureDataboxGatewayGroup', 'Service Azure Databox Gateway Group', 'an optional tech label') {
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDataboxGatewayGroup
include('azure-17/Item/Integration/ServiceAzureDataboxGateway')

' renders the element
ServiceAzureDataboxGatewayGroup('ServiceAzureDataboxGatewayGroup', 'Service Azure Databox Gateway Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

