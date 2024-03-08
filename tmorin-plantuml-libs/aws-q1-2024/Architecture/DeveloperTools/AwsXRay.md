# AwsXRay


```text
aws-q1-2024/Architecture/DeveloperTools/AwsXRay
```

```text
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')
```



| Illustration | AwsXRay | AwsXRayCard | AwsXRayGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/DeveloperTools/AwsXRay.png) | ![illustration for AwsXRay](../../../aws-q1-2024/Architecture/DeveloperTools/AwsXRay.Local.png) | ![illustration for AwsXRayCard](../../../aws-q1-2024/Architecture/DeveloperTools/AwsXRayCard.Local.png) | ![illustration for AwsXRayGroup](../../../aws-q1-2024/Architecture/DeveloperTools/AwsXRayGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsXRayXs>`
- `<$AwsXRaySm>`
- `<$AwsXRayMd>`
- `<$AwsXRayLg>`





## AwsXRay

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsXRay
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRay('AwsXRay', 'Aws X Ray', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsXRay
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRay('AwsXRay', 'Aws X Ray', 'an optional tech label', 'an optional description')
@enduml
```

## AwsXRayCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsXRayCard
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRayCard('AwsXRayCard', 'Aws X Ray Card', 'an optional description')
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

' loads the Item which embeds the element AwsXRayCard
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRayCard('AwsXRayCard', 'Aws X Ray Card', 'an optional description')
@enduml
```

## AwsXRayGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsXRayGroup
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRayGroup('AwsXRayGroup', 'Aws X Ray Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsXRayGroup
include('aws-q1-2024/Architecture/DeveloperTools/AwsXRay')

' renders the element
AwsXRayGroup('AwsXRayGroup', 'Aws X Ray Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

