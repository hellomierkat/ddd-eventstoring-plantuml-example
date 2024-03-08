# AmazonDynamoDbItems


```text
aws-q2-2023/Resource/Database/AmazonDynamoDbItems
```

```text
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')
```



| Illustration | AmazonDynamoDbItems | AmazonDynamoDbItemsCard | AmazonDynamoDbItemsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/Database/AmazonDynamoDbItems.png) | ![illustration for AmazonDynamoDbItems](../../../aws-q2-2023/Resource/Database/AmazonDynamoDbItems.Local.png) | ![illustration for AmazonDynamoDbItemsCard](../../../aws-q2-2023/Resource/Database/AmazonDynamoDbItemsCard.Local.png) | ![illustration for AmazonDynamoDbItemsGroup](../../../aws-q2-2023/Resource/Database/AmazonDynamoDbItemsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonDynamoDbItemsXs>`
- `<$AmazonDynamoDbItemsSm>`
- `<$AmazonDynamoDbItemsMd>`
- `<$AmazonDynamoDbItemsLg>`





## AmazonDynamoDbItems

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonDynamoDbItems
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItems('AmazonDynamoDbItems', 'Amazon Dynamo Db Items', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonDynamoDbItems
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItems('AmazonDynamoDbItems', 'Amazon Dynamo Db Items', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonDynamoDbItemsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonDynamoDbItemsCard
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItemsCard('AmazonDynamoDbItemsCard', 'Amazon Dynamo Db Items Card', 'an optional description')
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

' loads the Item which embeds the element AmazonDynamoDbItemsCard
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItemsCard('AmazonDynamoDbItemsCard', 'Amazon Dynamo Db Items Card', 'an optional description')
@enduml
```

## AmazonDynamoDbItemsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonDynamoDbItemsGroup
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItemsGroup('AmazonDynamoDbItemsGroup', 'Amazon Dynamo Db Items Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonDynamoDbItemsGroup
include('aws-q2-2023/Resource/Database/AmazonDynamoDbItems')

' renders the element
AmazonDynamoDbItemsGroup('AmazonDynamoDbItemsGroup', 'Amazon Dynamo Db Items Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

