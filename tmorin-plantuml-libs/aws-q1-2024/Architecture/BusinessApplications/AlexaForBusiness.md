# AlexaForBusiness


```text
aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness
```

```text
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')
```



| Illustration | AlexaForBusiness | AlexaForBusinessCard | AlexaForBusinessGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness.png) | ![illustration for AlexaForBusiness](../../../aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness.Local.png) | ![illustration for AlexaForBusinessCard](../../../aws-q1-2024/Architecture/BusinessApplications/AlexaForBusinessCard.Local.png) | ![illustration for AlexaForBusinessGroup](../../../aws-q1-2024/Architecture/BusinessApplications/AlexaForBusinessGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AlexaForBusinessXs>`
- `<$AlexaForBusinessSm>`
- `<$AlexaForBusinessMd>`
- `<$AlexaForBusinessLg>`





## AlexaForBusiness

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AlexaForBusiness
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusiness('AlexaForBusiness', 'Alexa For Business', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AlexaForBusiness
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusiness('AlexaForBusiness', 'Alexa For Business', 'an optional tech label', 'an optional description')
@enduml
```

## AlexaForBusinessCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AlexaForBusinessCard
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusinessCard('AlexaForBusinessCard', 'Alexa For Business Card', 'an optional description')
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

' loads the Item which embeds the element AlexaForBusinessCard
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusinessCard('AlexaForBusinessCard', 'Alexa For Business Card', 'an optional description')
@enduml
```

## AlexaForBusinessGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AlexaForBusinessGroup
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusinessGroup('AlexaForBusinessGroup', 'Alexa For Business Group', 'an optional tech label') {
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

' loads the Item which embeds the element AlexaForBusinessGroup
include('aws-q1-2024/Architecture/BusinessApplications/AlexaForBusiness')

' renders the element
AlexaForBusinessGroup('AlexaForBusinessGroup', 'Alexa For Business Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

