# AmazonSimpleQueueServiceQueue


```text
aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue
```

```text
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')
```



| Illustration | AmazonSimpleQueueServiceQueue | AmazonSimpleQueueServiceQueueCard | AmazonSimpleQueueServiceQueueGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue.png) | ![illustration for AmazonSimpleQueueServiceQueue](../../../aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue.Local.png) | ![illustration for AmazonSimpleQueueServiceQueueCard](../../../aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueueCard.Local.png) | ![illustration for AmazonSimpleQueueServiceQueueGroup](../../../aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueueGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonSimpleQueueServiceQueueXs>`
- `<$AmazonSimpleQueueServiceQueueSm>`
- `<$AmazonSimpleQueueServiceQueueMd>`
- `<$AmazonSimpleQueueServiceQueueLg>`





## AmazonSimpleQueueServiceQueue

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueue
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueue('AmazonSimpleQueueServiceQueue', 'Amazon Simple Queue Service Queue', 'an optional tech label', 'an optional description')
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueue
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueue('AmazonSimpleQueueServiceQueue', 'Amazon Simple Queue Service Queue', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonSimpleQueueServiceQueueCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueueCard
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueueCard('AmazonSimpleQueueServiceQueueCard', 'Amazon Simple Queue Service Queue Card', 'an optional description')
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueueCard
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueueCard('AmazonSimpleQueueServiceQueueCard', 'Amazon Simple Queue Service Queue Card', 'an optional description')
@enduml
```

## AmazonSimpleQueueServiceQueueGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueueGroup
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueueGroup('AmazonSimpleQueueServiceQueueGroup', 'Amazon Simple Queue Service Queue Group', 'an optional tech label') {
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonSimpleQueueServiceQueueGroup
include('aws-q2-2023/Resource/ApplicationIntegration/AmazonSimpleQueueServiceQueue')

' renders the element
AmazonSimpleQueueServiceQueueGroup('AmazonSimpleQueueServiceQueueGroup', 'Amazon Simple Queue Service Queue Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

