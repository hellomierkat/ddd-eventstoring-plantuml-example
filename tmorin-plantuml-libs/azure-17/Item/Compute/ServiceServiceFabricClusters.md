# ServiceServiceFabricClusters


```text
azure-17/Item/Compute/ServiceServiceFabricClusters
```

```text
include('azure-17/Item/Compute/ServiceServiceFabricClusters')
```



| Illustration | ServiceServiceFabricClusters | ServiceServiceFabricClustersCard | ServiceServiceFabricClustersGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Compute/ServiceServiceFabricClusters.png) | ![illustration for ServiceServiceFabricClusters](../../../azure-17/Item/Compute/ServiceServiceFabricClusters.Local.png) | ![illustration for ServiceServiceFabricClustersCard](../../../azure-17/Item/Compute/ServiceServiceFabricClustersCard.Local.png) | ![illustration for ServiceServiceFabricClustersGroup](../../../azure-17/Item/Compute/ServiceServiceFabricClustersGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceServiceFabricClustersXs>`
- `<$ServiceServiceFabricClustersSm>`
- `<$ServiceServiceFabricClustersMd>`
- `<$ServiceServiceFabricClustersLg>`





## ServiceServiceFabricClusters

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServiceFabricClusters
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClusters('ServiceServiceFabricClusters', 'Service Service Fabric Clusters', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceServiceFabricClusters
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClusters('ServiceServiceFabricClusters', 'Service Service Fabric Clusters', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceServiceFabricClustersCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServiceFabricClustersCard
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClustersCard('ServiceServiceFabricClustersCard', 'Service Service Fabric Clusters Card', 'an optional description')
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

' loads the Item which embeds the element ServiceServiceFabricClustersCard
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClustersCard('ServiceServiceFabricClustersCard', 'Service Service Fabric Clusters Card', 'an optional description')
@enduml
```

## ServiceServiceFabricClustersGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServiceFabricClustersGroup
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClustersGroup('ServiceServiceFabricClustersGroup', 'Service Service Fabric Clusters Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceServiceFabricClustersGroup
include('azure-17/Item/Compute/ServiceServiceFabricClusters')

' renders the element
ServiceServiceFabricClustersGroup('ServiceServiceFabricClustersGroup', 'Service Service Fabric Clusters Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

