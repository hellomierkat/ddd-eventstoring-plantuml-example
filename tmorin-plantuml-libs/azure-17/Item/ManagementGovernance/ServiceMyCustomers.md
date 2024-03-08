# ServiceMyCustomers


```text
azure-17/Item/ManagementGovernance/ServiceMyCustomers
```

```text
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')
```



| Illustration | ServiceMyCustomers | ServiceMyCustomersCard | ServiceMyCustomersGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/ManagementGovernance/ServiceMyCustomers.png) | ![illustration for ServiceMyCustomers](../../../azure-17/Item/ManagementGovernance/ServiceMyCustomers.Local.png) | ![illustration for ServiceMyCustomersCard](../../../azure-17/Item/ManagementGovernance/ServiceMyCustomersCard.Local.png) | ![illustration for ServiceMyCustomersGroup](../../../azure-17/Item/ManagementGovernance/ServiceMyCustomersGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceMyCustomersXs>`
- `<$ServiceMyCustomersSm>`
- `<$ServiceMyCustomersMd>`
- `<$ServiceMyCustomersLg>`





## ServiceMyCustomers

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMyCustomers
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomers('ServiceMyCustomers', 'Service My Customers', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceMyCustomers
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomers('ServiceMyCustomers', 'Service My Customers', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceMyCustomersCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMyCustomersCard
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomersCard('ServiceMyCustomersCard', 'Service My Customers Card', 'an optional description')
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

' loads the Item which embeds the element ServiceMyCustomersCard
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomersCard('ServiceMyCustomersCard', 'Service My Customers Card', 'an optional description')
@enduml
```

## ServiceMyCustomersGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceMyCustomersGroup
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomersGroup('ServiceMyCustomersGroup', 'Service My Customers Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceMyCustomersGroup
include('azure-17/Item/ManagementGovernance/ServiceMyCustomers')

' renders the element
ServiceMyCustomersGroup('ServiceMyCustomersGroup', 'Service My Customers Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

