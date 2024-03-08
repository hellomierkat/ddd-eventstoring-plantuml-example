# AmazonCloudWatchRule


```text
aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule
```

```text
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')
```



| Illustration | AmazonCloudWatchRule | AmazonCloudWatchRuleCard | AmazonCloudWatchRuleGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule.png) | ![illustration for AmazonCloudWatchRule](../../../aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule.Local.png) | ![illustration for AmazonCloudWatchRuleCard](../../../aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRuleCard.Local.png) | ![illustration for AmazonCloudWatchRuleGroup](../../../aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRuleGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonCloudWatchRuleXs>`
- `<$AmazonCloudWatchRuleSm>`
- `<$AmazonCloudWatchRuleMd>`
- `<$AmazonCloudWatchRuleLg>`





## AmazonCloudWatchRule

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonCloudWatchRule
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRule('AmazonCloudWatchRule', 'Amazon Cloud Watch Rule', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonCloudWatchRule
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRule('AmazonCloudWatchRule', 'Amazon Cloud Watch Rule', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonCloudWatchRuleCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonCloudWatchRuleCard
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRuleCard('AmazonCloudWatchRuleCard', 'Amazon Cloud Watch Rule Card', 'an optional description')
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

' loads the Item which embeds the element AmazonCloudWatchRuleCard
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRuleCard('AmazonCloudWatchRuleCard', 'Amazon Cloud Watch Rule Card', 'an optional description')
@enduml
```

## AmazonCloudWatchRuleGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AmazonCloudWatchRuleGroup
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRuleGroup('AmazonCloudWatchRuleGroup', 'Amazon Cloud Watch Rule Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonCloudWatchRuleGroup
include('aws-q2-2023/Resource/ManagementGovernance/AmazonCloudWatchRule')

' renders the element
AmazonCloudWatchRuleGroup('AmazonCloudWatchRuleGroup', 'Amazon Cloud Watch Rule Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

