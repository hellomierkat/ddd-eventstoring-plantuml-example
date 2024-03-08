# ServiceServerFarm


```text
azure-17/Item/General/ServiceServerFarm
```

```text
include('azure-17/Item/General/ServiceServerFarm')
```



| Illustration | ServiceServerFarm | ServiceServerFarmCard | ServiceServerFarmGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceServerFarm.png) | ![illustration for ServiceServerFarm](../../../azure-17/Item/General/ServiceServerFarm.Local.png) | ![illustration for ServiceServerFarmCard](../../../azure-17/Item/General/ServiceServerFarmCard.Local.png) | ![illustration for ServiceServerFarmGroup](../../../azure-17/Item/General/ServiceServerFarmGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceServerFarmXs>`
- `<$ServiceServerFarmSm>`
- `<$ServiceServerFarmMd>`
- `<$ServiceServerFarmLg>`





## ServiceServerFarm

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServerFarm
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarm('ServiceServerFarm', 'Service Server Farm', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceServerFarm
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarm('ServiceServerFarm', 'Service Server Farm', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceServerFarmCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServerFarmCard
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarmCard('ServiceServerFarmCard', 'Service Server Farm Card', 'an optional description')
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

' loads the Item which embeds the element ServiceServerFarmCard
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarmCard('ServiceServerFarmCard', 'Service Server Farm Card', 'an optional description')
@enduml
```

## ServiceServerFarmGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceServerFarmGroup
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarmGroup('ServiceServerFarmGroup', 'Service Server Farm Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceServerFarmGroup
include('azure-17/Item/General/ServiceServerFarm')

' renders the element
ServiceServerFarmGroup('ServiceServerFarmGroup', 'Service Server Farm Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

