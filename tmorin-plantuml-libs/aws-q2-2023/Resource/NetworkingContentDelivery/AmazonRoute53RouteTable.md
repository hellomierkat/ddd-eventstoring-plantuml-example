# AmazonRoute53RouteTable


```text
aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable
```

```text
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')
```



| Illustration | AmazonRoute53RouteTable | AmazonRoute53RouteTableCard | AmazonRoute53RouteTableGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable.png) | ![illustration for AmazonRoute53RouteTable](../../../aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable.Local.png) | ![illustration for AmazonRoute53RouteTableCard](../../../aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTableCard.Local.png) | ![illustration for AmazonRoute53RouteTableGroup](../../../aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTableGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonRoute53RouteTableXs>`
- `<$AmazonRoute53RouteTableSm>`
- `<$AmazonRoute53RouteTableMd>`
- `<$AmazonRoute53RouteTableLg>`





## AmazonRoute53RouteTable

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonRoute53RouteTable
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTable('AmazonRoute53RouteTable', 'Amazon Route53 Route Table', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonRoute53RouteTable
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTable('AmazonRoute53RouteTable', 'Amazon Route53 Route Table', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonRoute53RouteTableCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonRoute53RouteTableCard
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTableCard('AmazonRoute53RouteTableCard', 'Amazon Route53 Route Table Card', 'an optional description')
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

' loads the Item which embeds the element AmazonRoute53RouteTableCard
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTableCard('AmazonRoute53RouteTableCard', 'Amazon Route53 Route Table Card', 'an optional description')
@enduml
```

## AmazonRoute53RouteTableGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonRoute53RouteTableGroup
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTableGroup('AmazonRoute53RouteTableGroup', 'Amazon Route53 Route Table Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonRoute53RouteTableGroup
include('aws-q2-2023/Resource/NetworkingContentDelivery/AmazonRoute53RouteTable')

' renders the element
AmazonRoute53RouteTableGroup('AmazonRoute53RouteTableGroup', 'Amazon Route53 Route Table Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

