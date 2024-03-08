# Cancel


```text
material-4/Navigation/Cancel
```

```text
include('material-4/Navigation/Cancel')
```



| Illustration | Cancel |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/Cancel.png) | ![illustration for Cancel](../../material-4/Navigation/Cancel.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CancelXs>`
- `<$CancelSm>`
- `<$CancelMd>`
- `<$CancelLg>`





## Cancel

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Cancel
include('material-4/Navigation/Cancel')

' renders the element
Cancel('Cancel', 'Cancel', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cancel
include('material-4/Navigation/Cancel')

' renders the element
Cancel('Cancel', 'Cancel', 'an optional tech label', 'an optional description')
@enduml
```

