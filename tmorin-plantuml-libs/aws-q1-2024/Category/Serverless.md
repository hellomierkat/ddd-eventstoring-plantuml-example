# Serverless


```text
aws-q1-2024/Category/Serverless
```

```text
include('aws-q1-2024/Category/Serverless')
```



| Illustration | Serverless | ServerlessCard | ServerlessGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../aws-q1-2024/Category/Serverless.png) | ![illustration for Serverless](../../aws-q1-2024/Category/Serverless.Local.png) | ![illustration for ServerlessCard](../../aws-q1-2024/Category/ServerlessCard.Local.png) | ![illustration for ServerlessGroup](../../aws-q1-2024/Category/ServerlessGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServerlessXs>`
- `<$ServerlessSm>`
- `<$ServerlessMd>`
- `<$ServerlessLg>`





## Serverless

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element Serverless
include('aws-q1-2024/Category/Serverless')

' renders the element
Serverless('Serverless', 'Serverless', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element Serverless
include('aws-q1-2024/Category/Serverless')

' renders the element
Serverless('Serverless', 'Serverless', 'an optional tech label', 'an optional description')
@enduml
```

## ServerlessCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ServerlessCard
include('aws-q1-2024/Category/Serverless')

' renders the element
ServerlessCard('ServerlessCard', 'Serverless Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ServerlessCard
include('aws-q1-2024/Category/Serverless')

' renders the element
ServerlessCard('ServerlessCard', 'Serverless Card', 'an optional description')
@enduml
```

## ServerlessGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ServerlessGroup
include('aws-q1-2024/Category/Serverless')

' renders the element
ServerlessGroup('ServerlessGroup', 'Serverless Group', 'an optional tech label') {
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
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ServerlessGroup
include('aws-q1-2024/Category/Serverless')

' renders the element
ServerlessGroup('ServerlessGroup', 'Serverless Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

