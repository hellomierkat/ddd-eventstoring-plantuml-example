# FireExtinguisher


```text
fontawesome-6/Solid/FireExtinguisher
```

```text
include('fontawesome-6/Solid/FireExtinguisher')
```



| Illustration | FireExtinguisher |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FireExtinguisher.png) | ![illustration for FireExtinguisher](../../fontawesome-6/Solid/FireExtinguisher.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FireExtinguisherXs>`
- `<$FireExtinguisherSm>`
- `<$FireExtinguisherMd>`
- `<$FireExtinguisherLg>`





## FireExtinguisher

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FireExtinguisher
include('fontawesome-6/Solid/FireExtinguisher')

' renders the element
FireExtinguisher('FireExtinguisher', 'Fire Extinguisher', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FireExtinguisher
include('fontawesome-6/Solid/FireExtinguisher')

' renders the element
FireExtinguisher('FireExtinguisher', 'Fire Extinguisher', 'an optional tech label', 'an optional description')
@enduml
```

