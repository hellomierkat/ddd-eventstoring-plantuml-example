# ContactMail


```text
material-4/Communication/ContactMail
```

```text
include('material-4/Communication/ContactMail')
```



| Illustration | ContactMail |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/ContactMail.png) | ![illustration for ContactMail](../../material-4/Communication/ContactMail.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ContactMailXs>`
- `<$ContactMailSm>`
- `<$ContactMailMd>`
- `<$ContactMailLg>`





## ContactMail

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ContactMail
include('material-4/Communication/ContactMail')

' renders the element
ContactMail('ContactMail', 'Contact Mail', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ContactMail
include('material-4/Communication/ContactMail')

' renders the element
ContactMail('ContactMail', 'Contact Mail', 'an optional tech label', 'an optional description')
@enduml
```

