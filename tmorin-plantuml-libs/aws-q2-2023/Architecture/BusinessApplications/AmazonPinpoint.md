# AmazonPinpoint


```text
aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint
```

```text
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')
```



| Illustration | AmazonPinpoint | AmazonPinpointCard | AmazonPinpointGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint.png) | ![illustration for AmazonPinpoint](../../../aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint.Local.png) | ![illustration for AmazonPinpointCard](../../../aws-q2-2023/Architecture/BusinessApplications/AmazonPinpointCard.Local.png) | ![illustration for AmazonPinpointGroup](../../../aws-q2-2023/Architecture/BusinessApplications/AmazonPinpointGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonPinpointXs>`
- `<$AmazonPinpointSm>`
- `<$AmazonPinpointMd>`
- `<$AmazonPinpointLg>`





## AmazonPinpoint

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonPinpoint
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpoint('AmazonPinpoint', 'Amazon Pinpoint', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonPinpoint
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpoint('AmazonPinpoint', 'Amazon Pinpoint', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonPinpointCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonPinpointCard
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpointCard('AmazonPinpointCard', 'Amazon Pinpoint Card', 'an optional description')
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

' loads the Item which embeds the element AmazonPinpointCard
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpointCard('AmazonPinpointCard', 'Amazon Pinpoint Card', 'an optional description')
@enduml
```

## AmazonPinpointGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonPinpointGroup
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpointGroup('AmazonPinpointGroup', 'Amazon Pinpoint Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonPinpointGroup
include('aws-q2-2023/Architecture/BusinessApplications/AmazonPinpoint')

' renders the element
AmazonPinpointGroup('AmazonPinpointGroup', 'Amazon Pinpoint Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

