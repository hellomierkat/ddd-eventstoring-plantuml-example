# Vmware


```text
simpleicons-8/V/Vmware
```

```text
include('simpleicons-8/V/Vmware')
```



| Illustration | Vmware |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/V/Vmware.png) | ![illustration for Vmware](../../simpleicons-8/V/Vmware.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VmwareXs>`
- `<$VmwareSm>`
- `<$VmwareMd>`
- `<$VmwareLg>`





## Vmware

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Vmware
include('simpleicons-8/V/Vmware')

' renders the element
Vmware('Vmware', 'Vmware', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vmware
include('simpleicons-8/V/Vmware')

' renders the element
Vmware('Vmware', 'Vmware', 'an optional tech label', 'an optional description')
@enduml
```

