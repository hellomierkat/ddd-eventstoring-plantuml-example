# AwsCloudDevelopmentKit


```text
aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit
```

```text
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')
```



| Illustration | AwsCloudDevelopmentKit | AwsCloudDevelopmentKitCard | AwsCloudDevelopmentKitGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit.png) | ![illustration for AwsCloudDevelopmentKit](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit.Local.png) | ![illustration for AwsCloudDevelopmentKitCard](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKitCard.Local.png) | ![illustration for AwsCloudDevelopmentKitGroup](../../../aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKitGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsCloudDevelopmentKitXs>`
- `<$AwsCloudDevelopmentKitSm>`
- `<$AwsCloudDevelopmentKitMd>`
- `<$AwsCloudDevelopmentKitLg>`





## AwsCloudDevelopmentKit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCloudDevelopmentKit
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKit('AwsCloudDevelopmentKit', 'Aws Cloud Development Kit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsCloudDevelopmentKit
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKit('AwsCloudDevelopmentKit', 'Aws Cloud Development Kit', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCloudDevelopmentKitCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCloudDevelopmentKitCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKitCard('AwsCloudDevelopmentKitCard', 'Aws Cloud Development Kit Card', 'an optional description')
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

' loads the Item which embeds the element AwsCloudDevelopmentKitCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKitCard('AwsCloudDevelopmentKitCard', 'Aws Cloud Development Kit Card', 'an optional description')
@enduml
```

## AwsCloudDevelopmentKitGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsCloudDevelopmentKitGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKitGroup('AwsCloudDevelopmentKitGroup', 'Aws Cloud Development Kit Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsCloudDevelopmentKitGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsCloudDevelopmentKit')

' renders the element
AwsCloudDevelopmentKitGroup('AwsCloudDevelopmentKitGroup', 'Aws Cloud Development Kit Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

