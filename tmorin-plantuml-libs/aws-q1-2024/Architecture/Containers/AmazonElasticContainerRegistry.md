# AmazonElasticContainerRegistry


```text
aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry
```

```text
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')
```



| Illustration | AmazonElasticContainerRegistry | AmazonElasticContainerRegistryCard | AmazonElasticContainerRegistryGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry.png) | ![illustration for AmazonElasticContainerRegistry](../../../aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry.Local.png) | ![illustration for AmazonElasticContainerRegistryCard](../../../aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistryCard.Local.png) | ![illustration for AmazonElasticContainerRegistryGroup](../../../aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistryGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonElasticContainerRegistryXs>`
- `<$AmazonElasticContainerRegistrySm>`
- `<$AmazonElasticContainerRegistryMd>`
- `<$AmazonElasticContainerRegistryLg>`





## AmazonElasticContainerRegistry

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonElasticContainerRegistry
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistry('AmazonElasticContainerRegistry', 'Amazon Elastic Container Registry', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonElasticContainerRegistry
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistry('AmazonElasticContainerRegistry', 'Amazon Elastic Container Registry', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonElasticContainerRegistryCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonElasticContainerRegistryCard
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistryCard('AmazonElasticContainerRegistryCard', 'Amazon Elastic Container Registry Card', 'an optional description')
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

' loads the Item which embeds the element AmazonElasticContainerRegistryCard
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistryCard('AmazonElasticContainerRegistryCard', 'Amazon Elastic Container Registry Card', 'an optional description')
@enduml
```

## AmazonElasticContainerRegistryGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonElasticContainerRegistryGroup
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistryGroup('AmazonElasticContainerRegistryGroup', 'Amazon Elastic Container Registry Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonElasticContainerRegistryGroup
include('aws-q1-2024/Architecture/Containers/AmazonElasticContainerRegistry')

' renders the element
AmazonElasticContainerRegistryGroup('AmazonElasticContainerRegistryGroup', 'Amazon Elastic Container Registry Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

