# AwsToolsAndSdKs


```text
aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs
```

```text
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')
```



| Illustration | AwsToolsAndSdKs | AwsToolsAndSdKsCard | AwsToolsAndSdKsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs.png) | ![illustration for AwsToolsAndSdKs](../../../aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs.Local.png) | ![illustration for AwsToolsAndSdKsCard](../../../aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKsCard.Local.png) | ![illustration for AwsToolsAndSdKsGroup](../../../aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsToolsAndSdKsXs>`
- `<$AwsToolsAndSdKsSm>`
- `<$AwsToolsAndSdKsMd>`
- `<$AwsToolsAndSdKsLg>`





## AwsToolsAndSdKs

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsToolsAndSdKs
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKs('AwsToolsAndSdKs', 'Aws Tools And Sd Ks', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsToolsAndSdKs
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKs('AwsToolsAndSdKs', 'Aws Tools And Sd Ks', 'an optional tech label', 'an optional description')
@enduml
```

## AwsToolsAndSdKsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsToolsAndSdKsCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKsCard('AwsToolsAndSdKsCard', 'Aws Tools And Sd Ks Card', 'an optional description')
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

' loads the Item which embeds the element AwsToolsAndSdKsCard
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKsCard('AwsToolsAndSdKsCard', 'Aws Tools And Sd Ks Card', 'an optional description')
@enduml
```

## AwsToolsAndSdKsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsToolsAndSdKsGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKsGroup('AwsToolsAndSdKsGroup', 'Aws Tools And Sd Ks Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsToolsAndSdKsGroup
include('aws-q2-2023/Architecture/DeveloperTools/AwsToolsAndSdKs')

' renders the element
AwsToolsAndSdKsGroup('AwsToolsAndSdKsGroup', 'Aws Tools And Sd Ks Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

