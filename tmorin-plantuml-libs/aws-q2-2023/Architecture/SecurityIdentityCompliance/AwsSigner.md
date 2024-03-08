# AwsSigner


```text
aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner
```

```text
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')
```



| Illustration | AwsSigner | AwsSignerCard | AwsSignerGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner.png) | ![illustration for AwsSigner](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner.Local.png) | ![illustration for AwsSignerCard](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSignerCard.Local.png) | ![illustration for AwsSignerGroup](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSignerGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsSignerXs>`
- `<$AwsSignerSm>`
- `<$AwsSignerMd>`
- `<$AwsSignerLg>`





## AwsSigner

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSigner
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSigner('AwsSigner', 'Aws Signer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsSigner
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSigner('AwsSigner', 'Aws Signer', 'an optional tech label', 'an optional description')
@enduml
```

## AwsSignerCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSignerCard
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSignerCard('AwsSignerCard', 'Aws Signer Card', 'an optional description')
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

' loads the Item which embeds the element AwsSignerCard
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSignerCard('AwsSignerCard', 'Aws Signer Card', 'an optional description')
@enduml
```

## AwsSignerGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsSignerGroup
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSignerGroup('AwsSignerGroup', 'Aws Signer Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsSignerGroup
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsSigner')

' renders the element
AwsSignerGroup('AwsSignerGroup', 'Aws Signer Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

