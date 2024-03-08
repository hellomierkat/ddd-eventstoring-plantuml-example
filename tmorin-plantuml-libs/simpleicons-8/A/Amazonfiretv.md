# Amazonfiretv


```text
simpleicons-8/A/Amazonfiretv
```

```text
include('simpleicons-8/A/Amazonfiretv')
```



| Illustration | Amazonfiretv |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Amazonfiretv.png) | ![illustration for Amazonfiretv](../../simpleicons-8/A/Amazonfiretv.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonfiretvXs>`
- `<$AmazonfiretvSm>`
- `<$AmazonfiretvMd>`
- `<$AmazonfiretvLg>`





## Amazonfiretv

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Amazonfiretv
include('simpleicons-8/A/Amazonfiretv')

' renders the element
Amazonfiretv('Amazonfiretv', 'Amazonfiretv', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Amazonfiretv
include('simpleicons-8/A/Amazonfiretv')

' renders the element
Amazonfiretv('Amazonfiretv', 'Amazonfiretv', 'an optional tech label', 'an optional description')
@enduml
```

