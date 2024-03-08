# Safari


```text
simpleicons-8/S/Safari
```

```text
include('simpleicons-8/S/Safari')
```



| Illustration | Safari |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Safari.png) | ![illustration for Safari](../../simpleicons-8/S/Safari.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SafariXs>`
- `<$SafariSm>`
- `<$SafariMd>`
- `<$SafariLg>`





## Safari

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Safari
include('simpleicons-8/S/Safari')

' renders the element
Safari('Safari', 'Safari', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Safari
include('simpleicons-8/S/Safari')

' renders the element
Safari('Safari', 'Safari', 'an optional tech label', 'an optional description')
@enduml
```

