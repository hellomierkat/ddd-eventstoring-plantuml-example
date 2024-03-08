# Mongodb


```text
simpleicons-8/M/Mongodb
```

```text
include('simpleicons-8/M/Mongodb')
```



| Illustration | Mongodb |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Mongodb.png) | ![illustration for Mongodb](../../simpleicons-8/M/Mongodb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MongodbXs>`
- `<$MongodbSm>`
- `<$MongodbMd>`
- `<$MongodbLg>`





## Mongodb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Mongodb
include('simpleicons-8/M/Mongodb')

' renders the element
Mongodb('Mongodb', 'Mongodb', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mongodb
include('simpleicons-8/M/Mongodb')

' renders the element
Mongodb('Mongodb', 'Mongodb', 'an optional tech label', 'an optional description')
@enduml
```

