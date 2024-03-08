# ServiceJourneyHub


```text
azure-17/Item/General/ServiceJourneyHub
```

```text
include('azure-17/Item/General/ServiceJourneyHub')
```



| Illustration | ServiceJourneyHub | ServiceJourneyHubCard | ServiceJourneyHubGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceJourneyHub.png) | ![illustration for ServiceJourneyHub](../../../azure-17/Item/General/ServiceJourneyHub.Local.png) | ![illustration for ServiceJourneyHubCard](../../../azure-17/Item/General/ServiceJourneyHubCard.Local.png) | ![illustration for ServiceJourneyHubGroup](../../../azure-17/Item/General/ServiceJourneyHubGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceJourneyHubXs>`
- `<$ServiceJourneyHubSm>`
- `<$ServiceJourneyHubMd>`
- `<$ServiceJourneyHubLg>`





## ServiceJourneyHub

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceJourneyHub
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHub('ServiceJourneyHub', 'Service Journey Hub', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceJourneyHub
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHub('ServiceJourneyHub', 'Service Journey Hub', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceJourneyHubCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceJourneyHubCard
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHubCard('ServiceJourneyHubCard', 'Service Journey Hub Card', 'an optional description')
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

' loads the Item which embeds the element ServiceJourneyHubCard
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHubCard('ServiceJourneyHubCard', 'Service Journey Hub Card', 'an optional description')
@enduml
```

## ServiceJourneyHubGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceJourneyHubGroup
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHubGroup('ServiceJourneyHubGroup', 'Service Journey Hub Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceJourneyHubGroup
include('azure-17/Item/General/ServiceJourneyHub')

' renders the element
ServiceJourneyHubGroup('ServiceJourneyHubGroup', 'Service Journey Hub Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

