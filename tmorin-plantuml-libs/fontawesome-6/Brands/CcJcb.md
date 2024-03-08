# CcJcb


```text
fontawesome-6/Brands/CcJcb
```

```text
include('fontawesome-6/Brands/CcJcb')
```



| Illustration | CcJcb |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/CcJcb.png) | ![illustration for CcJcb](../../fontawesome-6/Brands/CcJcb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CcJcbXs>`
- `<$CcJcbSm>`
- `<$CcJcbMd>`
- `<$CcJcbLg>`





## CcJcb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CcJcb
include('fontawesome-6/Brands/CcJcb')

' renders the element
CcJcb('CcJcb', 'Cc Jcb', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CcJcb
include('fontawesome-6/Brands/CcJcb')

' renders the element
CcJcb('CcJcb', 'Cc Jcb', 'an optional tech label', 'an optional description')
@enduml
```

