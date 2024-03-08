# AwsSystemsManager


```text
aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager
```

```text
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')
```



| Illustration | AwsSystemsManager | AwsSystemsManagerCard | AwsSystemsManagerGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager.png) | ![illustration for AwsSystemsManager](../../../aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager.Local.png) | ![illustration for AwsSystemsManagerCard](../../../aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManagerCard.Local.png) | ![illustration for AwsSystemsManagerGroup](../../../aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManagerGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsSystemsManagerXs>`
- `<$AwsSystemsManagerSm>`
- `<$AwsSystemsManagerMd>`
- `<$AwsSystemsManagerLg>`





## AwsSystemsManager

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSystemsManager
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManager('AwsSystemsManager', 'Aws Systems Manager', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsSystemsManager
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManager('AwsSystemsManager', 'Aws Systems Manager', 'an optional tech label', 'an optional description')
@enduml
```

## AwsSystemsManagerCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSystemsManagerCard
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManagerCard('AwsSystemsManagerCard', 'Aws Systems Manager Card', 'an optional description')
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

' loads the Item which embeds the element AwsSystemsManagerCard
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManagerCard('AwsSystemsManagerCard', 'Aws Systems Manager Card', 'an optional description')
@enduml
```

## AwsSystemsManagerGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSystemsManagerGroup
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManagerGroup('AwsSystemsManagerGroup', 'Aws Systems Manager Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsSystemsManagerGroup
include('aws-q2-2023/Architecture/ManagementGovernance/AwsSystemsManager')

' renders the element
AwsSystemsManagerGroup('AwsSystemsManagerGroup', 'Aws Systems Manager Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

