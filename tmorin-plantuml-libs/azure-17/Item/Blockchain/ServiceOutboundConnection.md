# ServiceOutboundConnection


```text
azure-17/Item/Blockchain/ServiceOutboundConnection
```

```text
include('azure-17/Item/Blockchain/ServiceOutboundConnection')
```



| Illustration | ServiceOutboundConnection | ServiceOutboundConnectionCard | ServiceOutboundConnectionGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Blockchain/ServiceOutboundConnection.png) | ![illustration for ServiceOutboundConnection](../../../azure-17/Item/Blockchain/ServiceOutboundConnection.Local.png) | ![illustration for ServiceOutboundConnectionCard](../../../azure-17/Item/Blockchain/ServiceOutboundConnectionCard.Local.png) | ![illustration for ServiceOutboundConnectionGroup](../../../azure-17/Item/Blockchain/ServiceOutboundConnectionGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceOutboundConnectionXs>`
- `<$ServiceOutboundConnectionSm>`
- `<$ServiceOutboundConnectionMd>`
- `<$ServiceOutboundConnectionLg>`





## ServiceOutboundConnection

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceOutboundConnection
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnection('ServiceOutboundConnection', 'Service Outbound Connection', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceOutboundConnection
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnection('ServiceOutboundConnection', 'Service Outbound Connection', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceOutboundConnectionCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceOutboundConnectionCard
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnectionCard('ServiceOutboundConnectionCard', 'Service Outbound Connection Card', 'an optional description')
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

' loads the Item which embeds the element ServiceOutboundConnectionCard
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnectionCard('ServiceOutboundConnectionCard', 'Service Outbound Connection Card', 'an optional description')
@enduml
```

## ServiceOutboundConnectionGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceOutboundConnectionGroup
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnectionGroup('ServiceOutboundConnectionGroup', 'Service Outbound Connection Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceOutboundConnectionGroup
include('azure-17/Item/Blockchain/ServiceOutboundConnection')

' renders the element
ServiceOutboundConnectionGroup('ServiceOutboundConnectionGroup', 'Service Outbound Connection Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

