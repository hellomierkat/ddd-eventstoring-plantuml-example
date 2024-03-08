# Outbond


```text
material-4/Action/Outbond
```

```text
include('material-4/Action/Outbond')
```



| Illustration | Outbond |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Outbond.png) | ![illustration for Outbond](../../material-4/Action/Outbond.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OutbondXs>`
- `<$OutbondSm>`
- `<$OutbondMd>`
- `<$OutbondLg>`





## Outbond

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Outbond
include('material-4/Action/Outbond')

' renders the element
Outbond('Outbond', 'Outbond', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Outbond
include('material-4/Action/Outbond')

' renders the element
Outbond('Outbond', 'Outbond', 'an optional tech label', 'an optional description')
@enduml
```

