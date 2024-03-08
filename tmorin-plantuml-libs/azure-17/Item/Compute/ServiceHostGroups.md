# ServiceHostGroups


```text
azure-17/Item/Compute/ServiceHostGroups
```

```text
include('azure-17/Item/Compute/ServiceHostGroups')
```



| Illustration | ServiceHostGroups | ServiceHostGroupsCard | ServiceHostGroupsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Compute/ServiceHostGroups.png) | ![illustration for ServiceHostGroups](../../../azure-17/Item/Compute/ServiceHostGroups.Local.png) | ![illustration for ServiceHostGroupsCard](../../../azure-17/Item/Compute/ServiceHostGroupsCard.Local.png) | ![illustration for ServiceHostGroupsGroup](../../../azure-17/Item/Compute/ServiceHostGroupsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceHostGroupsXs>`
- `<$ServiceHostGroupsSm>`
- `<$ServiceHostGroupsMd>`
- `<$ServiceHostGroupsLg>`





## ServiceHostGroups

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceHostGroups
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroups('ServiceHostGroups', 'Service Host Groups', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceHostGroups
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroups('ServiceHostGroups', 'Service Host Groups', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceHostGroupsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceHostGroupsCard
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroupsCard('ServiceHostGroupsCard', 'Service Host Groups Card', 'an optional description')
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

' loads the Item which embeds the element ServiceHostGroupsCard
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroupsCard('ServiceHostGroupsCard', 'Service Host Groups Card', 'an optional description')
@enduml
```

## ServiceHostGroupsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceHostGroupsGroup
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroupsGroup('ServiceHostGroupsGroup', 'Service Host Groups Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceHostGroupsGroup
include('azure-17/Item/Compute/ServiceHostGroups')

' renders the element
ServiceHostGroupsGroup('ServiceHostGroupsGroup', 'Service Host Groups Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

