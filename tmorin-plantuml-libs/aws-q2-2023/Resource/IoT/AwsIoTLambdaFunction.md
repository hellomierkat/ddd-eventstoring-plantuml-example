# AwsIoTLambdaFunction


```text
aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction
```

```text
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')
```



| Illustration | AwsIoTLambdaFunction | AwsIoTLambdaFunctionCard | AwsIoTLambdaFunctionGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction.png) | ![illustration for AwsIoTLambdaFunction](../../../aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction.Local.png) | ![illustration for AwsIoTLambdaFunctionCard](../../../aws-q2-2023/Resource/IoT/AwsIoTLambdaFunctionCard.Local.png) | ![illustration for AwsIoTLambdaFunctionGroup](../../../aws-q2-2023/Resource/IoT/AwsIoTLambdaFunctionGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsIoTLambdaFunctionXs>`
- `<$AwsIoTLambdaFunctionSm>`
- `<$AwsIoTLambdaFunctionMd>`
- `<$AwsIoTLambdaFunctionLg>`





## AwsIoTLambdaFunction

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTLambdaFunction
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunction('AwsIoTLambdaFunction', 'Aws Io T Lambda Function', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsIoTLambdaFunction
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunction('AwsIoTLambdaFunction', 'Aws Io T Lambda Function', 'an optional tech label', 'an optional description')
@enduml
```

## AwsIoTLambdaFunctionCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTLambdaFunctionCard
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunctionCard('AwsIoTLambdaFunctionCard', 'Aws Io T Lambda Function Card', 'an optional description')
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

' loads the Item which embeds the element AwsIoTLambdaFunctionCard
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunctionCard('AwsIoTLambdaFunctionCard', 'Aws Io T Lambda Function Card', 'an optional description')
@enduml
```

## AwsIoTLambdaFunctionGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTLambdaFunctionGroup
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunctionGroup('AwsIoTLambdaFunctionGroup', 'Aws Io T Lambda Function Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsIoTLambdaFunctionGroup
include('aws-q2-2023/Resource/IoT/AwsIoTLambdaFunction')

' renders the element
AwsIoTLambdaFunctionGroup('AwsIoTLambdaFunctionGroup', 'Aws Io T Lambda Function Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

