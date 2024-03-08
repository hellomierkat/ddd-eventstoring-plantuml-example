# Amazon


```text
fontawesome-6/Brands/Amazon
```

```text
include('fontawesome-6/Brands/Amazon')
```



| Illustration | Amazon |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Amazon.png) | ![illustration for Amazon](../../fontawesome-6/Brands/Amazon.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonXs>`
- `<$AmazonSm>`
- `<$AmazonMd>`
- `<$AmazonLg>`





## Amazon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Amazon
include('fontawesome-6/Brands/Amazon')

' renders the element
Amazon('Amazon', 'Amazon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Amazon
include('fontawesome-6/Brands/Amazon')

' renders the element
Amazon('Amazon', 'Amazon', 'an optional tech label', 'an optional description')
@enduml
```

