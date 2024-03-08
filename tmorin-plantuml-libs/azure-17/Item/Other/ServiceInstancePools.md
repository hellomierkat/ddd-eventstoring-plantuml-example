# ServiceInstancePools


```text
azure-17/Item/Other/ServiceInstancePools
```

```text
include('azure-17/Item/Other/ServiceInstancePools')
```



| Illustration | ServiceInstancePools | ServiceInstancePoolsCard | ServiceInstancePoolsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Other/ServiceInstancePools.png) | ![illustration for ServiceInstancePools](../../../azure-17/Item/Other/ServiceInstancePools.Local.png) | ![illustration for ServiceInstancePoolsCard](../../../azure-17/Item/Other/ServiceInstancePoolsCard.Local.png) | ![illustration for ServiceInstancePoolsGroup](../../../azure-17/Item/Other/ServiceInstancePoolsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceInstancePoolsXs>`
- `<$ServiceInstancePoolsSm>`
- `<$ServiceInstancePoolsMd>`
- `<$ServiceInstancePoolsLg>`





## ServiceInstancePools

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceInstancePools
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePools('ServiceInstancePools', 'Service Instance Pools', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceInstancePools
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePools('ServiceInstancePools', 'Service Instance Pools', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceInstancePoolsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceInstancePoolsCard
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePoolsCard('ServiceInstancePoolsCard', 'Service Instance Pools Card', 'an optional description')
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

' loads the Item which embeds the element ServiceInstancePoolsCard
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePoolsCard('ServiceInstancePoolsCard', 'Service Instance Pools Card', 'an optional description')
@enduml
```

## ServiceInstancePoolsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceInstancePoolsGroup
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePoolsGroup('ServiceInstancePoolsGroup', 'Service Instance Pools Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceInstancePoolsGroup
include('azure-17/Item/Other/ServiceInstancePools')

' renders the element
ServiceInstancePoolsGroup('ServiceInstancePoolsGroup', 'Service Instance Pools Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

