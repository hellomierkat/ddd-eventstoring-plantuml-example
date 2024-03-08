# ServiceWorkspaces


```text
azure-17/Item/Compute/ServiceWorkspaces
```

```text
include('azure-17/Item/Compute/ServiceWorkspaces')
```



| Illustration | ServiceWorkspaces | ServiceWorkspacesCard | ServiceWorkspacesGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Compute/ServiceWorkspaces.png) | ![illustration for ServiceWorkspaces](../../../azure-17/Item/Compute/ServiceWorkspaces.Local.png) | ![illustration for ServiceWorkspacesCard](../../../azure-17/Item/Compute/ServiceWorkspacesCard.Local.png) | ![illustration for ServiceWorkspacesGroup](../../../azure-17/Item/Compute/ServiceWorkspacesGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceWorkspacesXs>`
- `<$ServiceWorkspacesSm>`
- `<$ServiceWorkspacesMd>`
- `<$ServiceWorkspacesLg>`





## ServiceWorkspaces

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkspaces
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspaces('ServiceWorkspaces', 'Service Workspaces', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceWorkspaces
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspaces('ServiceWorkspaces', 'Service Workspaces', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceWorkspacesCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkspacesCard
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspacesCard('ServiceWorkspacesCard', 'Service Workspaces Card', 'an optional description')
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

' loads the Item which embeds the element ServiceWorkspacesCard
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspacesCard('ServiceWorkspacesCard', 'Service Workspaces Card', 'an optional description')
@enduml
```

## ServiceWorkspacesGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkspacesGroup
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspacesGroup('ServiceWorkspacesGroup', 'Service Workspaces Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceWorkspacesGroup
include('azure-17/Item/Compute/ServiceWorkspaces')

' renders the element
ServiceWorkspacesGroup('ServiceWorkspacesGroup', 'Service Workspaces Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

