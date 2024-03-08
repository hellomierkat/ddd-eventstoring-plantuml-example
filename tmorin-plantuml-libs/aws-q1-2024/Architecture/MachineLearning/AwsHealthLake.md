# AwsHealthLake


```text
aws-q1-2024/Architecture/MachineLearning/AwsHealthLake
```

```text
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')
```



| Illustration | AwsHealthLake | AwsHealthLakeCard | AwsHealthLakeGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/MachineLearning/AwsHealthLake.png) | ![illustration for AwsHealthLake](../../../aws-q1-2024/Architecture/MachineLearning/AwsHealthLake.Local.png) | ![illustration for AwsHealthLakeCard](../../../aws-q1-2024/Architecture/MachineLearning/AwsHealthLakeCard.Local.png) | ![illustration for AwsHealthLakeGroup](../../../aws-q1-2024/Architecture/MachineLearning/AwsHealthLakeGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsHealthLakeXs>`
- `<$AwsHealthLakeSm>`
- `<$AwsHealthLakeMd>`
- `<$AwsHealthLakeLg>`





## AwsHealthLake

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsHealthLake
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLake('AwsHealthLake', 'Aws Health Lake', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsHealthLake
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLake('AwsHealthLake', 'Aws Health Lake', 'an optional tech label', 'an optional description')
@enduml
```

## AwsHealthLakeCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsHealthLakeCard
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLakeCard('AwsHealthLakeCard', 'Aws Health Lake Card', 'an optional description')
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

' loads the Item which embeds the element AwsHealthLakeCard
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLakeCard('AwsHealthLakeCard', 'Aws Health Lake Card', 'an optional description')
@enduml
```

## AwsHealthLakeGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AwsHealthLakeGroup
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLakeGroup('AwsHealthLakeGroup', 'Aws Health Lake Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsHealthLakeGroup
include('aws-q1-2024/Architecture/MachineLearning/AwsHealthLake')

' renders the element
AwsHealthLakeGroup('AwsHealthLakeGroup', 'Aws Health Lake Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

