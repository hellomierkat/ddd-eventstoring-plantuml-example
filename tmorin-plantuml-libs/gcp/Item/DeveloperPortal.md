# DeveloperPortal


```text
gcp/Item/DeveloperPortal
```

```text
include('gcp/Item/DeveloperPortal')
```



| Illustration | DeveloperPortal | DeveloperPortalCard | DeveloperPortalGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../gcp/Item/DeveloperPortal.png) | ![illustration for DeveloperPortal](../../gcp/Item/DeveloperPortal.Local.png) | ![illustration for DeveloperPortalCard](../../gcp/Item/DeveloperPortalCard.Local.png) | ![illustration for DeveloperPortalGroup](../../gcp/Item/DeveloperPortalGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DeveloperPortalXs>`
- `<$DeveloperPortalSm>`
- `<$DeveloperPortalMd>`
- `<$DeveloperPortalLg>`





## DeveloperPortal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortal
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortal('DeveloperPortal', 'Developer Portal', 'an optional tech label', 'an optional description')
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
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortal
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortal('DeveloperPortal', 'Developer Portal', 'an optional tech label', 'an optional description')
@enduml
```

## DeveloperPortalCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortalCard
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortalCard('DeveloperPortalCard', 'Developer Portal Card', 'an optional description')
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
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortalCard
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortalCard('DeveloperPortalCard', 'Developer Portal Card', 'an optional description')
@enduml
```

## DeveloperPortalGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortalGroup
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortalGroup('DeveloperPortalGroup', 'Developer Portal Group', 'an optional tech label') {
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
include('gcp/bootstrap')

' loads the Item which embeds the element DeveloperPortalGroup
include('gcp/Item/DeveloperPortal')

' renders the element
DeveloperPortalGroup('DeveloperPortalGroup', 'Developer Portal Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

