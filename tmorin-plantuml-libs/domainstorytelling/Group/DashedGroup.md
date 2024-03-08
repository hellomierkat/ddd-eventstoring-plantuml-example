# DashedGroup


```text
domainstorytelling/Group/DashedGroup
```

```text
include('domainstorytelling/Group/DashedGroup')
```



| DashedGroup |
| :---: |
| ![illustration for DashedGroup](../../domainstorytelling/Group/DashedGroup.Local.png) |







## DashedGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('domainstorytelling/bootstrap')

' loads the Item which embeds the element DashedGroup
include('domainstorytelling/Group/DashedGroup')

DashedGroup('DashedGroup', 'Dashed Group', 'an optional tech label') {
  note as note
  the content of the boundary
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
include('domainstorytelling/bootstrap')

' loads the Item which embeds the element DashedGroup
include('domainstorytelling/Group/DashedGroup')

DashedGroup('DashedGroup', 'Dashed Group', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

