# ManagementGovernance


```text
aws-q1-2024/Category/ManagementGovernance
```

```text
include('aws-q1-2024/Category/ManagementGovernance')
```



| Illustration | ManagementGovernance | ManagementGovernanceCard | ManagementGovernanceGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../aws-q1-2024/Category/ManagementGovernance.png) | ![illustration for ManagementGovernance](../../aws-q1-2024/Category/ManagementGovernance.Local.png) | ![illustration for ManagementGovernanceCard](../../aws-q1-2024/Category/ManagementGovernanceCard.Local.png) | ![illustration for ManagementGovernanceGroup](../../aws-q1-2024/Category/ManagementGovernanceGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ManagementGovernanceXs>`
- `<$ManagementGovernanceSm>`
- `<$ManagementGovernanceMd>`
- `<$ManagementGovernanceLg>`





## ManagementGovernance

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernance
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernance('ManagementGovernance', 'Management Governance', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernance
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernance('ManagementGovernance', 'Management Governance', 'an optional tech label', 'an optional description')
@enduml
```

## ManagementGovernanceCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernanceCard
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernanceCard('ManagementGovernanceCard', 'Management Governance Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernanceCard
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernanceCard('ManagementGovernanceCard', 'Management Governance Card', 'an optional description')
@enduml
```

## ManagementGovernanceGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernanceGroup
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernanceGroup('ManagementGovernanceGroup', 'Management Governance Group', 'an optional tech label') {
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
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ManagementGovernanceGroup
include('aws-q1-2024/Category/ManagementGovernance')

' renders the element
ManagementGovernanceGroup('ManagementGovernanceGroup', 'Management Governance Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

