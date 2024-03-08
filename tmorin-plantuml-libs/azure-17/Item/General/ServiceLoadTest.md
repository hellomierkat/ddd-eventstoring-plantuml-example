# ServiceLoadTest


```text
azure-17/Item/General/ServiceLoadTest
```

```text
include('azure-17/Item/General/ServiceLoadTest')
```



| Illustration | ServiceLoadTest | ServiceLoadTestCard | ServiceLoadTestGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceLoadTest.png) | ![illustration for ServiceLoadTest](../../../azure-17/Item/General/ServiceLoadTest.Local.png) | ![illustration for ServiceLoadTestCard](../../../azure-17/Item/General/ServiceLoadTestCard.Local.png) | ![illustration for ServiceLoadTestGroup](../../../azure-17/Item/General/ServiceLoadTestGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceLoadTestXs>`
- `<$ServiceLoadTestSm>`
- `<$ServiceLoadTestMd>`
- `<$ServiceLoadTestLg>`





## ServiceLoadTest

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceLoadTest
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTest('ServiceLoadTest', 'Service Load Test', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceLoadTest
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTest('ServiceLoadTest', 'Service Load Test', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceLoadTestCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceLoadTestCard
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTestCard('ServiceLoadTestCard', 'Service Load Test Card', 'an optional description')
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

' loads the Item which embeds the element ServiceLoadTestCard
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTestCard('ServiceLoadTestCard', 'Service Load Test Card', 'an optional description')
@enduml
```

## ServiceLoadTestGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceLoadTestGroup
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTestGroup('ServiceLoadTestGroup', 'Service Load Test Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceLoadTestGroup
include('azure-17/Item/General/ServiceLoadTest')

' renders the element
ServiceLoadTestGroup('ServiceLoadTestGroup', 'Service Load Test Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

