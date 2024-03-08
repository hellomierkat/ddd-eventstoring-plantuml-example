# AwsCodeDeploy


```text
aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy
```

```text
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')
```



| Illustration | AwsCodeDeploy | AwsCodeDeployCard | AwsCodeDeployGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy.png) | ![illustration for AwsCodeDeploy](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy.Local.png) | ![illustration for AwsCodeDeployCard](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeployCard.Local.png) | ![illustration for AwsCodeDeployGroup](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeployGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsCodeDeployXs>`
- `<$AwsCodeDeploySm>`
- `<$AwsCodeDeployMd>`
- `<$AwsCodeDeployLg>`





## AwsCodeDeploy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeDeploy
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeploy('AwsCodeDeploy', 'Aws Code Deploy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsCodeDeploy
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeploy('AwsCodeDeploy', 'Aws Code Deploy', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCodeDeployCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeDeployCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeployCard('AwsCodeDeployCard', 'Aws Code Deploy Card', 'an optional description')
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

' loads the Item which embeds the element AwsCodeDeployCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeployCard('AwsCodeDeployCard', 'Aws Code Deploy Card', 'an optional description')
@enduml
```

## AwsCodeDeployGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCodeDeployGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeployGroup('AwsCodeDeployGroup', 'Aws Code Deploy Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsCodeDeployGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCodeDeploy')

' renders the element
AwsCodeDeployGroup('AwsCodeDeployGroup', 'Aws Code Deploy Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

