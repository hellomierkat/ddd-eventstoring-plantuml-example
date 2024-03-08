# AwsOpsWorks


```text
aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks
```

```text
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')
```



| Illustration | AwsOpsWorks | AwsOpsWorksCard | AwsOpsWorksGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks.png) | ![illustration for AwsOpsWorks](../../../aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks.Local.png) | ![illustration for AwsOpsWorksCard](../../../aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorksCard.Local.png) | ![illustration for AwsOpsWorksGroup](../../../aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorksGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsOpsWorksXs>`
- `<$AwsOpsWorksSm>`
- `<$AwsOpsWorksMd>`
- `<$AwsOpsWorksLg>`





## AwsOpsWorks

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsOpsWorks
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorks('AwsOpsWorks', 'Aws Ops Works', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsOpsWorks
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorks('AwsOpsWorks', 'Aws Ops Works', 'an optional tech label', 'an optional description')
@enduml
```

## AwsOpsWorksCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsOpsWorksCard
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorksCard('AwsOpsWorksCard', 'Aws Ops Works Card', 'an optional description')
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

' loads the Item which embeds the element AwsOpsWorksCard
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorksCard('AwsOpsWorksCard', 'Aws Ops Works Card', 'an optional description')
@enduml
```

## AwsOpsWorksGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsOpsWorksGroup
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorksGroup('AwsOpsWorksGroup', 'Aws Ops Works Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsOpsWorksGroup
include('aws-q1-2024/Architecture/ManagementGovernance/AwsOpsWorks')

' renders the element
AwsOpsWorksGroup('AwsOpsWorksGroup', 'Aws Ops Works Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

