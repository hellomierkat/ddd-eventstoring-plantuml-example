# GroupExternalInfrastructure3rdParty


```text
gcp/Group/GroupExternalInfrastructure3rdParty
```

```text
include('gcp/Group/GroupExternalInfrastructure3rdParty')
```



| GroupExternalInfrastructure3rdParty |
| :---: |
| ![illustration for GroupExternalInfrastructure3rdParty](../../gcp/Group/GroupExternalInfrastructure3rdParty.Local.png) |







## GroupExternalInfrastructure3rdParty

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('gcp/bootstrap')

' loads the Item which embeds the element GroupExternalInfrastructure3rdParty
include('gcp/Group/GroupExternalInfrastructure3rdParty')

GroupExternalInfrastructure3rdParty('GroupExternalInfrastructure3rdParty', 'Group External Infrastructure3rd Party', 'an optional tech label') {
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

' loads the Item which embeds the element GroupExternalInfrastructure3rdParty
include('gcp/Group/GroupExternalInfrastructure3rdParty')

GroupExternalInfrastructure3rdParty('GroupExternalInfrastructure3rdParty', 'Group External Infrastructure3rd Party', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

