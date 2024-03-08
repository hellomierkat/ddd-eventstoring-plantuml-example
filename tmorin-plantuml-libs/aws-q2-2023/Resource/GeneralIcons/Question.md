# Question


```text
aws-q2-2023/Resource/GeneralIcons/Question
```

```text
include('aws-q2-2023/Resource/GeneralIcons/Question')
```



| Illustration | Question | QuestionCard | QuestionGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Resource/GeneralIcons/Question.png) | ![illustration for Question](../../../aws-q2-2023/Resource/GeneralIcons/Question.Local.png) | ![illustration for QuestionCard](../../../aws-q2-2023/Resource/GeneralIcons/QuestionCard.Local.png) | ![illustration for QuestionGroup](../../../aws-q2-2023/Resource/GeneralIcons/QuestionGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$QuestionXs>`
- `<$QuestionSm>`
- `<$QuestionMd>`
- `<$QuestionLg>`





## Question

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element Question
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
Question('Question', 'Question', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Question
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
Question('Question', 'Question', 'an optional tech label', 'an optional description')
@enduml
```

## QuestionCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element QuestionCard
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
QuestionCard('QuestionCard', 'Question Card', 'an optional description')
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

' loads the Item which embeds the element QuestionCard
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
QuestionCard('QuestionCard', 'Question Card', 'an optional description')
@enduml
```

## QuestionGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element QuestionGroup
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
QuestionGroup('QuestionGroup', 'Question Group', 'an optional tech label') {
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

' loads the Item which embeds the element QuestionGroup
include('aws-q2-2023/Resource/GeneralIcons/Question')

' renders the element
QuestionGroup('QuestionGroup', 'Question Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

