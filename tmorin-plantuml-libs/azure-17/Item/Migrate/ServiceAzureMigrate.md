# ServiceAzureMigrate


```text
azure-17/Item/Migrate/ServiceAzureMigrate
```

```text
include('azure-17/Item/Migrate/ServiceAzureMigrate')
```



| Illustration | ServiceAzureMigrate | ServiceAzureMigrateCard | ServiceAzureMigrateGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-17/Item/Migrate/ServiceAzureMigrate.png) | ![illustration for ServiceAzureMigrate](../../../azure-17/Item/Migrate/ServiceAzureMigrate.Local.png) | ![illustration for ServiceAzureMigrateCard](../../../azure-17/Item/Migrate/ServiceAzureMigrateCard.Local.png) | ![illustration for ServiceAzureMigrateGroup](../../../azure-17/Item/Migrate/ServiceAzureMigrateGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAzureMigrateXs>`
- `<$ServiceAzureMigrateSm>`
- `<$ServiceAzureMigrateMd>`
- `<$ServiceAzureMigrateLg>`





## ServiceAzureMigrate

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureMigrate
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrate('ServiceAzureMigrate', 'Service Azure Migrate', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureMigrate
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrate('ServiceAzureMigrate', 'Service Azure Migrate', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAzureMigrateCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureMigrateCard
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrateCard('ServiceAzureMigrateCard', 'Service Azure Migrate Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureMigrateCard
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrateCard('ServiceAzureMigrateCard', 'Service Azure Migrate Card', 'an optional description')
@enduml
```

## ServiceAzureMigrateGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element ServiceAzureMigrateGroup
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrateGroup('ServiceAzureMigrateGroup', 'Service Azure Migrate Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAzureMigrateGroup
include('azure-17/Item/Migrate/ServiceAzureMigrate')

' renders the element
ServiceAzureMigrateGroup('ServiceAzureMigrateGroup', 'Service Azure Migrate Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

