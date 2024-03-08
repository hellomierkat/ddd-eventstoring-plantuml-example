# AmazonEc2AutoScaling


```text
aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling
```

```text
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')
```



| Illustration | AmazonEc2AutoScaling | AmazonEc2AutoScalingCard | AmazonEc2AutoScalingGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling.png) | ![illustration for AmazonEc2AutoScaling](../../../aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling.Local.png) | ![illustration for AmazonEc2AutoScalingCard](../../../aws-q2-2023/Resource/Compute/AmazonEc2AutoScalingCard.Local.png) | ![illustration for AmazonEc2AutoScalingGroup](../../../aws-q2-2023/Resource/Compute/AmazonEc2AutoScalingGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonEc2AutoScalingXs>`
- `<$AmazonEc2AutoScalingSm>`
- `<$AmazonEc2AutoScalingMd>`
- `<$AmazonEc2AutoScalingLg>`





## AmazonEc2AutoScaling

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEc2AutoScaling
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScaling('AmazonEc2AutoScaling', 'Amazon Ec2 Auto Scaling', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonEc2AutoScaling
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScaling('AmazonEc2AutoScaling', 'Amazon Ec2 Auto Scaling', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonEc2AutoScalingCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEc2AutoScalingCard
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScalingCard('AmazonEc2AutoScalingCard', 'Amazon Ec2 Auto Scaling Card', 'an optional description')
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

' loads the Item which embeds the element AmazonEc2AutoScalingCard
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScalingCard('AmazonEc2AutoScalingCard', 'Amazon Ec2 Auto Scaling Card', 'an optional description')
@enduml
```

## AmazonEc2AutoScalingGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonEc2AutoScalingGroup
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScalingGroup('AmazonEc2AutoScalingGroup', 'Amazon Ec2 Auto Scaling Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonEc2AutoScalingGroup
include('aws-q2-2023/Resource/Compute/AmazonEc2AutoScaling')

' renders the element
AmazonEc2AutoScalingGroup('AmazonEc2AutoScalingGroup', 'Amazon Ec2 Auto Scaling Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

