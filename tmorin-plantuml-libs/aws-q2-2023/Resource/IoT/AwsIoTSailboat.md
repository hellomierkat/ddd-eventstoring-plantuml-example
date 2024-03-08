# AwsIoTSailboat


```text
aws-q2-2023/Resource/IoT/AwsIoTSailboat
```

```text
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')
```



| Illustration | AwsIoTSailboat | AwsIoTSailboatCard | AwsIoTSailboatGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/IoT/AwsIoTSailboat.png) | ![illustration for AwsIoTSailboat](../../../aws-q2-2023/Resource/IoT/AwsIoTSailboat.Local.png) | ![illustration for AwsIoTSailboatCard](../../../aws-q2-2023/Resource/IoT/AwsIoTSailboatCard.Local.png) | ![illustration for AwsIoTSailboatGroup](../../../aws-q2-2023/Resource/IoT/AwsIoTSailboatGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsIoTSailboatXs>`
- `<$AwsIoTSailboatSm>`
- `<$AwsIoTSailboatMd>`
- `<$AwsIoTSailboatLg>`





## AwsIoTSailboat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTSailboat
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboat('AwsIoTSailboat', 'Aws Io T Sailboat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsIoTSailboat
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboat('AwsIoTSailboat', 'Aws Io T Sailboat', 'an optional tech label', 'an optional description')
@enduml
```

## AwsIoTSailboatCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTSailboatCard
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboatCard('AwsIoTSailboatCard', 'Aws Io T Sailboat Card', 'an optional description')
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

' loads the Item which embeds the element AwsIoTSailboatCard
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboatCard('AwsIoTSailboatCard', 'Aws Io T Sailboat Card', 'an optional description')
@enduml
```

## AwsIoTSailboatGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsIoTSailboatGroup
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboatGroup('AwsIoTSailboatGroup', 'Aws Io T Sailboat Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsIoTSailboatGroup
include('aws-q2-2023/Resource/IoT/AwsIoTSailboat')

' renders the element
AwsIoTSailboatGroup('AwsIoTSailboatGroup', 'Aws Io T Sailboat Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

