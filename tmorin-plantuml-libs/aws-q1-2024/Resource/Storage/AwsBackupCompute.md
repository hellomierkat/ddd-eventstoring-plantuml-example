# AwsBackupCompute


```text
aws-q1-2024/Resource/Storage/AwsBackupCompute
```

```text
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')
```



| Illustration | AwsBackupCompute | AwsBackupComputeCard | AwsBackupComputeGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/Storage/AwsBackupCompute.png) | ![illustration for AwsBackupCompute](../../../aws-q1-2024/Resource/Storage/AwsBackupCompute.Local.png) | ![illustration for AwsBackupComputeCard](../../../aws-q1-2024/Resource/Storage/AwsBackupComputeCard.Local.png) | ![illustration for AwsBackupComputeGroup](../../../aws-q1-2024/Resource/Storage/AwsBackupComputeGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsBackupComputeXs>`
- `<$AwsBackupComputeSm>`
- `<$AwsBackupComputeMd>`
- `<$AwsBackupComputeLg>`





## AwsBackupCompute

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsBackupCompute
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupCompute('AwsBackupCompute', 'Aws Backup Compute', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsBackupCompute
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupCompute('AwsBackupCompute', 'Aws Backup Compute', 'an optional tech label', 'an optional description')
@enduml
```

## AwsBackupComputeCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsBackupComputeCard
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupComputeCard('AwsBackupComputeCard', 'Aws Backup Compute Card', 'an optional description')
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

' loads the Item which embeds the element AwsBackupComputeCard
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupComputeCard('AwsBackupComputeCard', 'Aws Backup Compute Card', 'an optional description')
@enduml
```

## AwsBackupComputeGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsBackupComputeGroup
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupComputeGroup('AwsBackupComputeGroup', 'Aws Backup Compute Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsBackupComputeGroup
include('aws-q1-2024/Resource/Storage/AwsBackupCompute')

' renders the element
AwsBackupComputeGroup('AwsBackupComputeGroup', 'Aws Backup Compute Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

