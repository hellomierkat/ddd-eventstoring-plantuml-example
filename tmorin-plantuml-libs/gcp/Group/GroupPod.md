# GroupPod


```text
gcp/Group/GroupPod
```

```text
include('gcp/Group/GroupPod')
```



| GroupPod |
| :---: |
| ![illustration for GroupPod](../../gcp/Group/GroupPod.Local.png) |







## GroupPod

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('gcp/bootstrap')

' loads the Item which embeds the element GroupPod
include('gcp/Group/GroupPod')

GroupPod('GroupPod', 'Group Pod', 'an optional tech label') {
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
include('gcp/bootstrap')

' loads the Item which embeds the element GroupPod
include('gcp/Group/GroupPod')

GroupPod('GroupPod', 'Group Pod', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

