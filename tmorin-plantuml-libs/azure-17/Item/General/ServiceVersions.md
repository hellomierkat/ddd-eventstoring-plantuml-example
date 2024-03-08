# ServiceVersions


```text
azure-17/Item/General/ServiceVersions
```

```text
include('azure-17/Item/General/ServiceVersions')
```



| Illustration | ServiceVersions | ServiceVersionsCard | ServiceVersionsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceVersions.png) | ![illustration for ServiceVersions](../../../azure-17/Item/General/ServiceVersions.Local.png) | ![illustration for ServiceVersionsCard](../../../azure-17/Item/General/ServiceVersionsCard.Local.png) | ![illustration for ServiceVersionsGroup](../../../azure-17/Item/General/ServiceVersionsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceVersionsXs>`
- `<$ServiceVersionsSm>`
- `<$ServiceVersionsMd>`
- `<$ServiceVersionsLg>`





## ServiceVersions

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceVersions
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersions('ServiceVersions', 'Service Versions', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceVersions
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersions('ServiceVersions', 'Service Versions', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceVersionsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceVersionsCard
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersionsCard('ServiceVersionsCard', 'Service Versions Card', 'an optional description')
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

' loads the Item which embeds the element ServiceVersionsCard
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersionsCard('ServiceVersionsCard', 'Service Versions Card', 'an optional description')
@enduml
```

## ServiceVersionsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceVersionsGroup
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersionsGroup('ServiceVersionsGroup', 'Service Versions Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceVersionsGroup
include('azure-17/Item/General/ServiceVersions')

' renders the element
ServiceVersionsGroup('ServiceVersionsGroup', 'Service Versions Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

