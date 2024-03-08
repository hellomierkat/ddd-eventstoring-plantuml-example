# VMwareCloudOnAws


```text
aws-q2-2023/Architecture/Compute/VMwareCloudOnAws
```

```text
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')
```



| Illustration | VMwareCloudOnAws | VMwareCloudOnAwsCard | VMwareCloudOnAwsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/Compute/VMwareCloudOnAws.png) | ![illustration for VMwareCloudOnAws](../../../aws-q2-2023/Architecture/Compute/VMwareCloudOnAws.Local.png) | ![illustration for VMwareCloudOnAwsCard](../../../aws-q2-2023/Architecture/Compute/VMwareCloudOnAwsCard.Local.png) | ![illustration for VMwareCloudOnAwsGroup](../../../aws-q2-2023/Architecture/Compute/VMwareCloudOnAwsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VMwareCloudOnAwsXs>`
- `<$VMwareCloudOnAwsSm>`
- `<$VMwareCloudOnAwsMd>`
- `<$VMwareCloudOnAwsLg>`





## VMwareCloudOnAws

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element VMwareCloudOnAws
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAws('VMwareCloudOnAws', 'V Mware Cloud On Aws', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element VMwareCloudOnAws
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAws('VMwareCloudOnAws', 'V Mware Cloud On Aws', 'an optional tech label', 'an optional description')
@enduml
```

## VMwareCloudOnAwsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element VMwareCloudOnAwsCard
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAwsCard('VMwareCloudOnAwsCard', 'V Mware Cloud On Aws Card', 'an optional description')
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

' loads the Item which embeds the element VMwareCloudOnAwsCard
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAwsCard('VMwareCloudOnAwsCard', 'V Mware Cloud On Aws Card', 'an optional description')
@enduml
```

## VMwareCloudOnAwsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element VMwareCloudOnAwsGroup
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAwsGroup('VMwareCloudOnAwsGroup', 'V Mware Cloud On Aws Group', 'an optional tech label') {
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

' loads the Item which embeds the element VMwareCloudOnAwsGroup
include('aws-q2-2023/Architecture/Compute/VMwareCloudOnAws')

' renders the element
VMwareCloudOnAwsGroup('VMwareCloudOnAwsGroup', 'V Mware Cloud On Aws Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

