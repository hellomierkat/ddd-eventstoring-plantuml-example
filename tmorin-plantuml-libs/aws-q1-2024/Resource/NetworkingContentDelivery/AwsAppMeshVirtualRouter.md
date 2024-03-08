# AwsAppMeshVirtualRouter


```text
aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter
```

```text
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')
```



| Illustration | AwsAppMeshVirtualRouter | AwsAppMeshVirtualRouterCard | AwsAppMeshVirtualRouterGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter.png) | ![illustration for AwsAppMeshVirtualRouter](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter.Local.png) | ![illustration for AwsAppMeshVirtualRouterCard](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouterCard.Local.png) | ![illustration for AwsAppMeshVirtualRouterGroup](../../../aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouterGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsAppMeshVirtualRouterXs>`
- `<$AwsAppMeshVirtualRouterSm>`
- `<$AwsAppMeshVirtualRouterMd>`
- `<$AwsAppMeshVirtualRouterLg>`





## AwsAppMeshVirtualRouter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsAppMeshVirtualRouter
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouter('AwsAppMeshVirtualRouter', 'Aws App Mesh Virtual Router', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsAppMeshVirtualRouter
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouter('AwsAppMeshVirtualRouter', 'Aws App Mesh Virtual Router', 'an optional tech label', 'an optional description')
@enduml
```

## AwsAppMeshVirtualRouterCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsAppMeshVirtualRouterCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouterCard('AwsAppMeshVirtualRouterCard', 'Aws App Mesh Virtual Router Card', 'an optional description')
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

' loads the Item which embeds the element AwsAppMeshVirtualRouterCard
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouterCard('AwsAppMeshVirtualRouterCard', 'Aws App Mesh Virtual Router Card', 'an optional description')
@enduml
```

## AwsAppMeshVirtualRouterGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsAppMeshVirtualRouterGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouterGroup('AwsAppMeshVirtualRouterGroup', 'Aws App Mesh Virtual Router Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsAppMeshVirtualRouterGroup
include('aws-q1-2024/Resource/NetworkingContentDelivery/AwsAppMeshVirtualRouter')

' renders the element
AwsAppMeshVirtualRouterGroup('AwsAppMeshVirtualRouterGroup', 'Aws App Mesh Virtual Router Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

