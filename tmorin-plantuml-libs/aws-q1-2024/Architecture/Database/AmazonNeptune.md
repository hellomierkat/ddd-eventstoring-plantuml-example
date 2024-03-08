# AmazonNeptune


```text
aws-q1-2024/Architecture/Database/AmazonNeptune
```

```text
include('aws-q1-2024/Architecture/Database/AmazonNeptune')
```



| Illustration | AmazonNeptune | AmazonNeptuneCard | AmazonNeptuneGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Architecture/Database/AmazonNeptune.png) | ![illustration for AmazonNeptune](../../../aws-q1-2024/Architecture/Database/AmazonNeptune.Local.png) | ![illustration for AmazonNeptuneCard](../../../aws-q1-2024/Architecture/Database/AmazonNeptuneCard.Local.png) | ![illustration for AmazonNeptuneGroup](../../../aws-q1-2024/Architecture/Database/AmazonNeptuneGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonNeptuneXs>`
- `<$AmazonNeptuneSm>`
- `<$AmazonNeptuneMd>`
- `<$AmazonNeptuneLg>`





## AmazonNeptune

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonNeptune
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptune('AmazonNeptune', 'Amazon Neptune', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonNeptune
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptune('AmazonNeptune', 'Amazon Neptune', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonNeptuneCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonNeptuneCard
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptuneCard('AmazonNeptuneCard', 'Amazon Neptune Card', 'an optional description')
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

' loads the Item which embeds the element AmazonNeptuneCard
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptuneCard('AmazonNeptuneCard', 'Amazon Neptune Card', 'an optional description')
@enduml
```

## AmazonNeptuneGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element AmazonNeptuneGroup
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptuneGroup('AmazonNeptuneGroup', 'Amazon Neptune Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonNeptuneGroup
include('aws-q1-2024/Architecture/Database/AmazonNeptune')

' renders the element
AmazonNeptuneGroup('AmazonNeptuneGroup', 'Amazon Neptune Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

