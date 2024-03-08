# Sdk


```text
aws-q1-2024/Resource/GeneralIcons/Sdk
```

```text
include('aws-q1-2024/Resource/GeneralIcons/Sdk')
```



| Illustration | Sdk | SdkCard | SdkGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/GeneralIcons/Sdk.png) | ![illustration for Sdk](../../../aws-q1-2024/Resource/GeneralIcons/Sdk.Local.png) | ![illustration for SdkCard](../../../aws-q1-2024/Resource/GeneralIcons/SdkCard.Local.png) | ![illustration for SdkGroup](../../../aws-q1-2024/Resource/GeneralIcons/SdkGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SdkXs>`
- `<$SdkSm>`
- `<$SdkMd>`
- `<$SdkLg>`





## Sdk

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element Sdk
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
Sdk('Sdk', 'Sdk', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sdk
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
Sdk('Sdk', 'Sdk', 'an optional tech label', 'an optional description')
@enduml
```

## SdkCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element SdkCard
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
SdkCard('SdkCard', 'Sdk Card', 'an optional description')
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

' loads the Item which embeds the element SdkCard
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
SdkCard('SdkCard', 'Sdk Card', 'an optional description')
@enduml
```

## SdkGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element SdkGroup
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
SdkGroup('SdkGroup', 'Sdk Group', 'an optional tech label') {
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

' loads the Item which embeds the element SdkGroup
include('aws-q1-2024/Resource/GeneralIcons/Sdk')

' renders the element
SdkGroup('SdkGroup', 'Sdk Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

