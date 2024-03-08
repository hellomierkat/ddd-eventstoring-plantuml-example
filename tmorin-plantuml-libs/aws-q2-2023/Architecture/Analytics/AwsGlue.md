# AwsGlue


```text
aws-q2-2023/Architecture/Analytics/AwsGlue
```

```text
include('aws-q2-2023/Architecture/Analytics/AwsGlue')
```



| Illustration | AwsGlue | AwsGlueCard | AwsGlueGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/Analytics/AwsGlue.png) | ![illustration for AwsGlue](../../../aws-q2-2023/Architecture/Analytics/AwsGlue.Local.png) | ![illustration for AwsGlueCard](../../../aws-q2-2023/Architecture/Analytics/AwsGlueCard.Local.png) | ![illustration for AwsGlueGroup](../../../aws-q2-2023/Architecture/Analytics/AwsGlueGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsGlueXs>`
- `<$AwsGlueSm>`
- `<$AwsGlueMd>`
- `<$AwsGlueLg>`





## AwsGlue

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlue
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlue('AwsGlue', 'Aws Glue', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsGlue
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlue('AwsGlue', 'Aws Glue', 'an optional tech label', 'an optional description')
@enduml
```

## AwsGlueCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlueCard
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlueCard('AwsGlueCard', 'Aws Glue Card', 'an optional description')
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

' loads the Item which embeds the element AwsGlueCard
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlueCard('AwsGlueCard', 'Aws Glue Card', 'an optional description')
@enduml
```

## AwsGlueGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsGlueGroup
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlueGroup('AwsGlueGroup', 'Aws Glue Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsGlueGroup
include('aws-q2-2023/Architecture/Analytics/AwsGlue')

' renders the element
AwsGlueGroup('AwsGlueGroup', 'Aws Glue Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

