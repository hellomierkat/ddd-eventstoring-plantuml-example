# PhoneEnabled


```text
material-4/Communication/PhoneEnabled
```

```text
include('material-4/Communication/PhoneEnabled')
```



| Illustration | PhoneEnabled |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/PhoneEnabled.png) | ![illustration for PhoneEnabled](../../material-4/Communication/PhoneEnabled.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PhoneEnabledXs>`
- `<$PhoneEnabledSm>`
- `<$PhoneEnabledMd>`
- `<$PhoneEnabledLg>`





## PhoneEnabled

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PhoneEnabled
include('material-4/Communication/PhoneEnabled')

' renders the element
PhoneEnabled('PhoneEnabled', 'Phone Enabled', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PhoneEnabled
include('material-4/Communication/PhoneEnabled')

' renders the element
PhoneEnabled('PhoneEnabled', 'Phone Enabled', 'an optional tech label', 'an optional description')
@enduml
```

