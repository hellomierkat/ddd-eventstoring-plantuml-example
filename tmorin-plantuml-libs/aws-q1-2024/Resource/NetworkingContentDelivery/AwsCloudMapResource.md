# AwsCloudMapResource


```text
aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource
```

```text
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')
```



| Illustration | AwsCloudMapResource | AwsCloudMapResourceCard | AwsCloudMapResourceGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource.png) | ![illustration for AwsCloudMapResource](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource.Local.png) | ![illustration for AwsCloudMapResourceCard](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResourceCard.Local.png) | ![illustration for AwsCloudMapResourceGroup](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResourceGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsCloudMapResourceXs>`
- `<$AwsCloudMapResourceSm>`
- `<$AwsCloudMapResourceMd>`
- `<$AwsCloudMapResourceLg>`





## AwsCloudMapResource

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudMapResource
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResource('AwsCloudMapResource', 'Aws Cloud Map Resource', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsCloudMapResource
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResource('AwsCloudMapResource', 'Aws Cloud Map Resource', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCloudMapResourceCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudMapResourceCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResourceCard('AwsCloudMapResourceCard', 'Aws Cloud Map Resource Card', 'an optional description')
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

' loads the Item which embeds the element AwsCloudMapResourceCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResourceCard('AwsCloudMapResourceCard', 'Aws Cloud Map Resource Card', 'an optional description')
@enduml
```

## AwsCloudMapResourceGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudMapResourceGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResourceGroup('AwsCloudMapResourceGroup', 'Aws Cloud Map Resource Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsCloudMapResourceGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsCloudMapResource')

' renders the element
AwsCloudMapResourceGroup('AwsCloudMapResourceGroup', 'Aws Cloud Map Resource Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

