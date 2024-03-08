# GroupDotted


```text
azure-17/Group/GroupDotted
```

```text
include('azure-17/Group/GroupDotted')
```



| GroupDotted |
| :---: |
| ![illustration for GroupDotted](../../azure-17/Group/GroupDotted.Local.png) |







## GroupDotted

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-17/bootstrap')

' loads the Item which embeds the element GroupDotted
include('azure-17/Group/GroupDotted')

GroupDotted('GroupDotted', 'Group Dotted', 'an optional tech label') {
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
include('azure-17/bootstrap')

' loads the Item which embeds the element GroupDotted
include('azure-17/Group/GroupDotted')

GroupDotted('GroupDotted', 'Group Dotted', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

