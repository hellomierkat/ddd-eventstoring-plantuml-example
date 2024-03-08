# ServiceControlsHorizontal


```text
azure-17/Item/General/ServiceControlsHorizontal
```

```text
include('azure-17/Item/General/ServiceControlsHorizontal')
```



| Illustration | ServiceControlsHorizontal | ServiceControlsHorizontalCard | ServiceControlsHorizontalGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServiceControlsHorizontal.png) | ![illustration for ServiceControlsHorizontal](../../../azure-17/Item/General/ServiceControlsHorizontal.Local.png) | ![illustration for ServiceControlsHorizontalCard](../../../azure-17/Item/General/ServiceControlsHorizontalCard.Local.png) | ![illustration for ServiceControlsHorizontalGroup](../../../azure-17/Item/General/ServiceControlsHorizontalGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceControlsHorizontalXs>`
- `<$ServiceControlsHorizontalSm>`
- `<$ServiceControlsHorizontalMd>`
- `<$ServiceControlsHorizontalLg>`





## ServiceControlsHorizontal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceControlsHorizontal
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontal('ServiceControlsHorizontal', 'Service Controls Horizontal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceControlsHorizontal
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontal('ServiceControlsHorizontal', 'Service Controls Horizontal', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceControlsHorizontalCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceControlsHorizontalCard
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontalCard('ServiceControlsHorizontalCard', 'Service Controls Horizontal Card', 'an optional description')
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

' loads the Item which embeds the element ServiceControlsHorizontalCard
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontalCard('ServiceControlsHorizontalCard', 'Service Controls Horizontal Card', 'an optional description')
@enduml
```

## ServiceControlsHorizontalGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceControlsHorizontalGroup
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontalGroup('ServiceControlsHorizontalGroup', 'Service Controls Horizontal Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceControlsHorizontalGroup
include('azure-17/Item/General/ServiceControlsHorizontal')

' renders the element
ServiceControlsHorizontalGroup('ServiceControlsHorizontalGroup', 'Service Controls Horizontal Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

