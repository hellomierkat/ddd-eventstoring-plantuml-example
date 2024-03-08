# AwsVerifiedAccess


```text
aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess
```

```text
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')
```



| Illustration | AwsVerifiedAccess | AwsVerifiedAccessCard | AwsVerifiedAccessGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess.png) | ![illustration for AwsVerifiedAccess](../../../aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess.Local.png) | ![illustration for AwsVerifiedAccessCard](../../../aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccessCard.Local.png) | ![illustration for AwsVerifiedAccessGroup](../../../aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccessGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsVerifiedAccessXs>`
- `<$AwsVerifiedAccessSm>`
- `<$AwsVerifiedAccessMd>`
- `<$AwsVerifiedAccessLg>`





## AwsVerifiedAccess

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsVerifiedAccess
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccess('AwsVerifiedAccess', 'Aws Verified Access', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsVerifiedAccess
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccess('AwsVerifiedAccess', 'Aws Verified Access', 'an optional tech label', 'an optional description')
@enduml
```

## AwsVerifiedAccessCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsVerifiedAccessCard
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccessCard('AwsVerifiedAccessCard', 'Aws Verified Access Card', 'an optional description')
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

' loads the Item which embeds the element AwsVerifiedAccessCard
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccessCard('AwsVerifiedAccessCard', 'Aws Verified Access Card', 'an optional description')
@enduml
```

## AwsVerifiedAccessGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsVerifiedAccessGroup
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccessGroup('AwsVerifiedAccessGroup', 'Aws Verified Access Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsVerifiedAccessGroup
include('aws-q1-2024/Architecture/NetworkingContentDelivery/AwsVerifiedAccess')

' renders the element
AwsVerifiedAccessGroup('AwsVerifiedAccessGroup', 'Aws Verified Access Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

