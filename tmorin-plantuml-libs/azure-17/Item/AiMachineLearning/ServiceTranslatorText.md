# ServiceTranslatorText


```text
azure-17/Item/AiMachineLearning/ServiceTranslatorText
```

```text
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')
```



| Illustration | ServiceTranslatorText | ServiceTranslatorTextCard | ServiceTranslatorTextGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/AiMachineLearning/ServiceTranslatorText.png) | ![illustration for ServiceTranslatorText](../../../azure-17/Item/AiMachineLearning/ServiceTranslatorText.Local.png) | ![illustration for ServiceTranslatorTextCard](../../../azure-17/Item/AiMachineLearning/ServiceTranslatorTextCard.Local.png) | ![illustration for ServiceTranslatorTextGroup](../../../azure-17/Item/AiMachineLearning/ServiceTranslatorTextGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceTranslatorTextXs>`
- `<$ServiceTranslatorTextSm>`
- `<$ServiceTranslatorTextMd>`
- `<$ServiceTranslatorTextLg>`





## ServiceTranslatorText

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorText
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorText('ServiceTranslatorText', 'Service Translator Text', 'an optional tech label', 'an optional description')
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorText
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorText('ServiceTranslatorText', 'Service Translator Text', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceTranslatorTextCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorTextCard
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorTextCard('ServiceTranslatorTextCard', 'Service Translator Text Card', 'an optional description')
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorTextCard
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorTextCard('ServiceTranslatorTextCard', 'Service Translator Text Card', 'an optional description')
@enduml
```

## ServiceTranslatorTextGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorTextGroup
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorTextGroup('ServiceTranslatorTextGroup', 'Service Translator Text Group', 'an optional tech label') {
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
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceTranslatorTextGroup
include('azure-17/Item/AiMachineLearning/ServiceTranslatorText')

' renders the element
ServiceTranslatorTextGroup('ServiceTranslatorTextGroup', 'Service Translator Text Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

