# Phone


```text
material-4/Communication/Phone
```

```text
include('material-4/Communication/Phone')
```



| Illustration | Phone |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/Phone.png) | ![illustration for Phone](../../material-4/Communication/Phone.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PhoneXs>`
- `<$PhoneSm>`
- `<$PhoneMd>`
- `<$PhoneLg>`





## Phone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Phone
include('material-4/Communication/Phone')

' renders the element
Phone('Phone', 'Phone', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Phone
include('material-4/Communication/Phone')

' renders the element
Phone('Phone', 'Phone', 'an optional tech label', 'an optional description')
@enduml
```

