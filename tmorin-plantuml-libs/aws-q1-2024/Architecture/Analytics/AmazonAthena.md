# AmazonAthena


```text
aws-q1-2024/Architecture/Analytics/AmazonAthena
```

```text
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')
```



| Illustration | AmazonAthena | AmazonAthenaCard | AmazonAthenaGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/Analytics/AmazonAthena.png) | ![illustration for AmazonAthena](../../../aws-q1-2024/Architecture/Analytics/AmazonAthena.Local.png) | ![illustration for AmazonAthenaCard](../../../aws-q1-2024/Architecture/Analytics/AmazonAthenaCard.Local.png) | ![illustration for AmazonAthenaGroup](../../../aws-q1-2024/Architecture/Analytics/AmazonAthenaGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonAthenaXs>`
- `<$AmazonAthenaSm>`
- `<$AmazonAthenaMd>`
- `<$AmazonAthenaLg>`





## AmazonAthena

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthena
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthena('AmazonAthena', 'Amazon Athena', 'an optional tech label', 'an optional description')
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthena
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthena('AmazonAthena', 'Amazon Athena', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonAthenaCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthenaCard
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthenaCard('AmazonAthenaCard', 'Amazon Athena Card', 'an optional description')
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthenaCard
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthenaCard('AmazonAthenaCard', 'Amazon Athena Card', 'an optional description')
@enduml
```

## AmazonAthenaGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthenaGroup
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthenaGroup('AmazonAthenaGroup', 'Amazon Athena Group', 'an optional tech label') {
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
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonAthenaGroup
include('aws-q1-2024/Architecture/Analytics/AmazonAthena')

' renders the element
AmazonAthenaGroup('AmazonAthenaGroup', 'Amazon Athena Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

