# AwsCloudShell


```text
aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell
```

```text
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')
```



| Illustration | AwsCloudShell | AwsCloudShellCard | AwsCloudShellGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell.png) | ![illustration for AwsCloudShell](../../../aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell.Local.png) | ![illustration for AwsCloudShellCard](../../../aws-q1-2024/Architecture/DeveloperTools/AwsCloudShellCard.Local.png) | ![illustration for AwsCloudShellGroup](../../../aws-q1-2024/Architecture/DeveloperTools/AwsCloudShellGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsCloudShellXs>`
- `<$AwsCloudShellSm>`
- `<$AwsCloudShellMd>`
- `<$AwsCloudShellLg>`





## AwsCloudShell

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudShell
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShell('AwsCloudShell', 'Aws Cloud Shell', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsCloudShell
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShell('AwsCloudShell', 'Aws Cloud Shell', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCloudShellCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudShellCard
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShellCard('AwsCloudShellCard', 'Aws Cloud Shell Card', 'an optional description')
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

' loads the Item which embeds the element AwsCloudShellCard
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShellCard('AwsCloudShellCard', 'Aws Cloud Shell Card', 'an optional description')
@enduml
```

## AwsCloudShellGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsCloudShellGroup
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShellGroup('AwsCloudShellGroup', 'Aws Cloud Shell Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsCloudShellGroup
include('aws-q1-2024/Architecture/DeveloperTools/AwsCloudShell')

' renders the element
AwsCloudShellGroup('AwsCloudShellGroup', 'Aws Cloud Shell Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

