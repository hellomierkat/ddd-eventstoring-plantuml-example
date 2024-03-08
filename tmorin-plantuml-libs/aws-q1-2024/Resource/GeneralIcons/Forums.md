# Forums


```text
aws-q1-2024/Resource/GeneralIcons/Forums
```

```text
include('aws-q1-2024/Resource/GeneralIcons/Forums')
```



| Illustration | Forums | ForumsCard | ForumsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2024/Resource/GeneralIcons/Forums.png) | ![illustration for Forums](../../../aws-q1-2024/Resource/GeneralIcons/Forums.Local.png) | ![illustration for ForumsCard](../../../aws-q1-2024/Resource/GeneralIcons/ForumsCard.Local.png) | ![illustration for ForumsGroup](../../../aws-q1-2024/Resource/GeneralIcons/ForumsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ForumsXs>`
- `<$ForumsSm>`
- `<$ForumsMd>`
- `<$ForumsLg>`





## Forums

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element Forums
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
Forums('Forums', 'Forums', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Forums
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
Forums('Forums', 'Forums', 'an optional tech label', 'an optional description')
@enduml
```

## ForumsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ForumsCard
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
ForumsCard('ForumsCard', 'Forums Card', 'an optional description')
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

' loads the Item which embeds the element ForumsCard
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
ForumsCard('ForumsCard', 'Forums Card', 'an optional description')
@enduml
```

## ForumsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2024/bootstrap')

' loads the Item which embeds the element ForumsGroup
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
ForumsGroup('ForumsGroup', 'Forums Group', 'an optional tech label') {
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

' loads the Item which embeds the element ForumsGroup
include('aws-q1-2024/Resource/GeneralIcons/Forums')

' renders the element
ForumsGroup('ForumsGroup', 'Forums Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

