# ServiceMetrics


```text
azure-17/Item/ManagementGovernance/ServiceMetrics
```

```text
include('azure-17/Item/ManagementGovernance/ServiceMetrics')
```



| Illustration | ServiceMetrics | ServiceMetricsCard | ServiceMetricsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/ManagementGovernance/ServiceMetrics.png) | ![illustration for ServiceMetrics](../../../azure-17/Item/ManagementGovernance/ServiceMetrics.Local.png) | ![illustration for ServiceMetricsCard](../../../azure-17/Item/ManagementGovernance/ServiceMetricsCard.Local.png) | ![illustration for ServiceMetricsGroup](../../../azure-17/Item/ManagementGovernance/ServiceMetricsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceMetricsXs>`
- `<$ServiceMetricsSm>`
- `<$ServiceMetricsMd>`
- `<$ServiceMetricsLg>`





## ServiceMetrics

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMetrics
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetrics('ServiceMetrics', 'Service Metrics', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceMetrics
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetrics('ServiceMetrics', 'Service Metrics', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceMetricsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMetricsCard
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetricsCard('ServiceMetricsCard', 'Service Metrics Card', 'an optional description')
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

' loads the Item which embeds the element ServiceMetricsCard
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetricsCard('ServiceMetricsCard', 'Service Metrics Card', 'an optional description')
@enduml
```

## ServiceMetricsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMetricsGroup
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetricsGroup('ServiceMetricsGroup', 'Service Metrics Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceMetricsGroup
include('azure-17/Item/ManagementGovernance/ServiceMetrics')

' renders the element
ServiceMetricsGroup('ServiceMetricsGroup', 'Service Metrics Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

