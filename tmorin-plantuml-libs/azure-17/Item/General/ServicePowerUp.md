# ServicePowerUp


```text
azure-17/Item/General/ServicePowerUp
```

```text
include('azure-17/Item/General/ServicePowerUp')
```



| Illustration | ServicePowerUp | ServicePowerUpCard | ServicePowerUpGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/General/ServicePowerUp.png) | ![illustration for ServicePowerUp](../../../azure-17/Item/General/ServicePowerUp.Local.png) | ![illustration for ServicePowerUpCard](../../../azure-17/Item/General/ServicePowerUpCard.Local.png) | ![illustration for ServicePowerUpGroup](../../../azure-17/Item/General/ServicePowerUpGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServicePowerUpXs>`
- `<$ServicePowerUpSm>`
- `<$ServicePowerUpMd>`
- `<$ServicePowerUpLg>`





## ServicePowerUp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServicePowerUp
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUp('ServicePowerUp', 'Service Power Up', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServicePowerUp
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUp('ServicePowerUp', 'Service Power Up', 'an optional tech label', 'an optional description')
@enduml
```

## ServicePowerUpCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServicePowerUpCard
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUpCard('ServicePowerUpCard', 'Service Power Up Card', 'an optional description')
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

' loads the Item which embeds the element ServicePowerUpCard
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUpCard('ServicePowerUpCard', 'Service Power Up Card', 'an optional description')
@enduml
```

## ServicePowerUpGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServicePowerUpGroup
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUpGroup('ServicePowerUpGroup', 'Service Power Up Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServicePowerUpGroup
include('azure-17/Item/General/ServicePowerUp')

' renders the element
ServicePowerUpGroup('ServicePowerUpGroup', 'Service Power Up Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

