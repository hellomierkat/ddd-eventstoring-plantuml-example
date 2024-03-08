# AwsGlobalAccelerator


```text
aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator
```

```text
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')
```



| Illustration | AwsGlobalAccelerator | AwsGlobalAcceleratorCard | AwsGlobalAcceleratorGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator.png) | ![illustration for AwsGlobalAccelerator](../../../aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator.Local.png) | ![illustration for AwsGlobalAcceleratorCard](../../../aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAcceleratorCard.Local.png) | ![illustration for AwsGlobalAcceleratorGroup](../../../aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAcceleratorGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsGlobalAcceleratorXs>`
- `<$AwsGlobalAcceleratorSm>`
- `<$AwsGlobalAcceleratorMd>`
- `<$AwsGlobalAcceleratorLg>`





## AwsGlobalAccelerator

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlobalAccelerator
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAccelerator('AwsGlobalAccelerator', 'Aws Global Accelerator', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsGlobalAccelerator
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAccelerator('AwsGlobalAccelerator', 'Aws Global Accelerator', 'an optional tech label', 'an optional description')
@enduml
```

## AwsGlobalAcceleratorCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlobalAcceleratorCard
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAcceleratorCard('AwsGlobalAcceleratorCard', 'Aws Global Accelerator Card', 'an optional description')
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

' loads the Item which embeds the element AwsGlobalAcceleratorCard
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAcceleratorCard('AwsGlobalAcceleratorCard', 'Aws Global Accelerator Card', 'an optional description')
@enduml
```

## AwsGlobalAcceleratorGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlobalAcceleratorGroup
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAcceleratorGroup('AwsGlobalAcceleratorGroup', 'Aws Global Accelerator Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsGlobalAcceleratorGroup
include('aws-q2-2023/Architecture/NetworkingContentDelivery/AwsGlobalAccelerator')

' renders the element
AwsGlobalAcceleratorGroup('AwsGlobalAcceleratorGroup', 'Aws Global Accelerator Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

