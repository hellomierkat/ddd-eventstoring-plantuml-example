# Mail


```text
material-4/Content/Mail
```

```text
include('material-4/Content/Mail')
```



| Illustration | Mail |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Content/Mail.png) | ![illustration for Mail](../../material-4/Content/Mail.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MailXs>`
- `<$MailSm>`
- `<$MailMd>`
- `<$MailLg>`





## Mail

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Mail
include('material-4/Content/Mail')

' renders the element
Mail('Mail', 'Mail', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mail
include('material-4/Content/Mail')

' renders the element
Mail('Mail', 'Mail', 'an optional tech label', 'an optional description')
@enduml
```

