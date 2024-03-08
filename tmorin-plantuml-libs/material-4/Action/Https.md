# Https


```text
material-4/Action/Https
```

```text
include('material-4/Action/Https')
```



| Illustration | Https |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Https.png) | ![illustration for Https](../../material-4/Action/Https.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HttpsXs>`
- `<$HttpsSm>`
- `<$HttpsMd>`
- `<$HttpsLg>`





## Https

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Https
include('material-4/Action/Https')

' renders the element
Https('Https', 'Https', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Https
include('material-4/Action/Https')

' renders the element
Https('Https', 'Https', 'an optional tech label', 'an optional description')
@enduml
```

