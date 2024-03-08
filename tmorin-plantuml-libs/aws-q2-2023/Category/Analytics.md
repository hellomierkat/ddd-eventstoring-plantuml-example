# Analytics


```text
aws-q2-2023/Category/Analytics
```

```text
include('aws-q2-2023/Category/Analytics')
```



| Illustration | Analytics | AnalyticsCard | AnalyticsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../aws-q2-2023/Category/Analytics.png) | ![illustration for Analytics](../../aws-q2-2023/Category/Analytics.Local.png) | ![illustration for AnalyticsCard](../../aws-q2-2023/Category/AnalyticsCard.Local.png) | ![illustration for AnalyticsGroup](../../aws-q2-2023/Category/AnalyticsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AnalyticsXs>`
- `<$AnalyticsSm>`
- `<$AnalyticsMd>`
- `<$AnalyticsLg>`





## Analytics

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element Analytics
include('aws-q2-2023/Category/Analytics')

' renders the element
Analytics('Analytics', 'Analytics', 'an optional tech label', 'an optional description')
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element Analytics
include('aws-q2-2023/Category/Analytics')

' renders the element
Analytics('Analytics', 'Analytics', 'an optional tech label', 'an optional description')
@enduml
```

## AnalyticsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AnalyticsCard
include('aws-q2-2023/Category/Analytics')

' renders the element
AnalyticsCard('AnalyticsCard', 'Analytics Card', 'an optional description')
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AnalyticsCard
include('aws-q2-2023/Category/Analytics')

' renders the element
AnalyticsCard('AnalyticsCard', 'Analytics Card', 'an optional description')
@enduml
```

## AnalyticsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AnalyticsGroup
include('aws-q2-2023/Category/Analytics')

' renders the element
AnalyticsGroup('AnalyticsGroup', 'Analytics Group', 'an optional tech label') {
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
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AnalyticsGroup
include('aws-q2-2023/Category/Analytics')

' renders the element
AnalyticsGroup('AnalyticsGroup', 'Analytics Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

