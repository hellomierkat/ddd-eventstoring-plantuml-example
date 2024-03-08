# ServiceAbsMember


```text
azure-17/Item/Blockchain/ServiceAbsMember
```

```text
include('azure-17/Item/Blockchain/ServiceAbsMember')
```



| Illustration | ServiceAbsMember | ServiceAbsMemberCard | ServiceAbsMemberGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Blockchain/ServiceAbsMember.png) | ![illustration for ServiceAbsMember](../../../azure-17/Item/Blockchain/ServiceAbsMember.Local.png) | ![illustration for ServiceAbsMemberCard](../../../azure-17/Item/Blockchain/ServiceAbsMemberCard.Local.png) | ![illustration for ServiceAbsMemberGroup](../../../azure-17/Item/Blockchain/ServiceAbsMemberGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAbsMemberXs>`
- `<$ServiceAbsMemberSm>`
- `<$ServiceAbsMemberMd>`
- `<$ServiceAbsMemberLg>`





## ServiceAbsMember

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAbsMember
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMember('ServiceAbsMember', 'Service Abs Member', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAbsMember
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMember('ServiceAbsMember', 'Service Abs Member', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAbsMemberCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAbsMemberCard
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMemberCard('ServiceAbsMemberCard', 'Service Abs Member Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAbsMemberCard
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMemberCard('ServiceAbsMemberCard', 'Service Abs Member Card', 'an optional description')
@enduml
```

## ServiceAbsMemberGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAbsMemberGroup
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMemberGroup('ServiceAbsMemberGroup', 'Service Abs Member Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAbsMemberGroup
include('azure-17/Item/Blockchain/ServiceAbsMember')

' renders the element
ServiceAbsMemberGroup('ServiceAbsMemberGroup', 'Service Abs Member Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

