# Database


```text
c4model/Element/Database
```

```text
include('c4model/Element/Database')
```



| Database |
| :---: |
| ![illustration for Database](../../c4model/Element/Database.Local.png) |




## Database

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('c4model/bootstrap')

' loads the Item which embeds the element Database
include('c4model/Element/Database')

Database('Database', 'Database', 'an optional description label', 'an optional tech label')
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
include('c4model/bootstrap')

' loads the Item which embeds the element Database
include('c4model/Element/Database')

Database('Database', 'Database', 'an optional description label', 'an optional tech label')
@enduml
```

