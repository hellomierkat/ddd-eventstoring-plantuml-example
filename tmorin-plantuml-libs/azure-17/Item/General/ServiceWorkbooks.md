# ServiceWorkbooks


```text
azure-17/Item/General/ServiceWorkbooks
```

```text
include('azure-17/Item/General/ServiceWorkbooks')
```



| Illustration | ServiceWorkbooks | ServiceWorkbooksCard | ServiceWorkbooksGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceWorkbooks.png) | ![illustration for ServiceWorkbooks](../../../azure-17/Item/General/ServiceWorkbooks.Local.png) | ![illustration for ServiceWorkbooksCard](../../../azure-17/Item/General/ServiceWorkbooksCard.Local.png) | ![illustration for ServiceWorkbooksGroup](../../../azure-17/Item/General/ServiceWorkbooksGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceWorkbooksXs>`
- `<$ServiceWorkbooksSm>`
- `<$ServiceWorkbooksMd>`
- `<$ServiceWorkbooksLg>`





## ServiceWorkbooks

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkbooks
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooks('ServiceWorkbooks', 'Service Workbooks', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceWorkbooks
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooks('ServiceWorkbooks', 'Service Workbooks', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceWorkbooksCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkbooksCard
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooksCard('ServiceWorkbooksCard', 'Service Workbooks Card', 'an optional description')
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

' loads the Item which embeds the element ServiceWorkbooksCard
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooksCard('ServiceWorkbooksCard', 'Service Workbooks Card', 'an optional description')
@enduml
```

## ServiceWorkbooksGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceWorkbooksGroup
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooksGroup('ServiceWorkbooksGroup', 'Service Workbooks Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceWorkbooksGroup
include('azure-17/Item/General/ServiceWorkbooks')

' renders the element
ServiceWorkbooksGroup('ServiceWorkbooksGroup', 'Service Workbooks Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

