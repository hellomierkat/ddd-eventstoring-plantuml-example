# Domain


```text
material-4/Social/Domain
```

```text
include('material-4/Social/Domain')
```



| Illustration | Domain |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/Domain.png) | ![illustration for Domain](../../material-4/Social/Domain.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DomainXs>`
- `<$DomainSm>`
- `<$DomainMd>`
- `<$DomainLg>`





## Domain

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Domain
include('material-4/Social/Domain')

' renders the element
Domain('Domain', 'Domain', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Domain
include('material-4/Social/Domain')

' renders the element
Domain('Domain', 'Domain', 'an optional tech label', 'an optional description')
@enduml
```

