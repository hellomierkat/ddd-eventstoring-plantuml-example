# ServiceAzureDeploymentEnvironments


```text
azure-17/Item/Other/ServiceAzureDeploymentEnvironments
```

```text
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')
```



| Illustration | ServiceAzureDeploymentEnvironments | ServiceAzureDeploymentEnvironmentsCard | ServiceAzureDeploymentEnvironmentsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Other/ServiceAzureDeploymentEnvironments.png) | ![illustration for ServiceAzureDeploymentEnvironments](../../../azure-17/Item/Other/ServiceAzureDeploymentEnvironments.Local.png) | ![illustration for ServiceAzureDeploymentEnvironmentsCard](../../../azure-17/Item/Other/ServiceAzureDeploymentEnvironmentsCard.Local.png) | ![illustration for ServiceAzureDeploymentEnvironmentsGroup](../../../azure-17/Item/Other/ServiceAzureDeploymentEnvironmentsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAzureDeploymentEnvironmentsXs>`
- `<$ServiceAzureDeploymentEnvironmentsSm>`
- `<$ServiceAzureDeploymentEnvironmentsMd>`
- `<$ServiceAzureDeploymentEnvironmentsLg>`





## ServiceAzureDeploymentEnvironments

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDeploymentEnvironments
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironments('ServiceAzureDeploymentEnvironments', 'Service Azure Deployment Environments', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureDeploymentEnvironments
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironments('ServiceAzureDeploymentEnvironments', 'Service Azure Deployment Environments', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAzureDeploymentEnvironmentsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDeploymentEnvironmentsCard
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironmentsCard('ServiceAzureDeploymentEnvironmentsCard', 'Service Azure Deployment Environments Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureDeploymentEnvironmentsCard
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironmentsCard('ServiceAzureDeploymentEnvironmentsCard', 'Service Azure Deployment Environments Card', 'an optional description')
@enduml
```

## ServiceAzureDeploymentEnvironmentsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureDeploymentEnvironmentsGroup
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironmentsGroup('ServiceAzureDeploymentEnvironmentsGroup', 'Service Azure Deployment Environments Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAzureDeploymentEnvironmentsGroup
include('azure-17/Item/Other/ServiceAzureDeploymentEnvironments')

' renders the element
ServiceAzureDeploymentEnvironmentsGroup('ServiceAzureDeploymentEnvironmentsGroup', 'Service Azure Deployment Environments Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

