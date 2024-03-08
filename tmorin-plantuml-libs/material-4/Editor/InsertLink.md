# InsertLink


```text
material-4/Editor/InsertLink
```

```text
include('material-4/Editor/InsertLink')
```



| Illustration | InsertLink |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/InsertLink.png) | ![illustration for InsertLink](../../material-4/Editor/InsertLink.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$InsertLinkXs>`
- `<$InsertLinkSm>`
- `<$InsertLinkMd>`
- `<$InsertLinkLg>`





## InsertLink

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element InsertLink
include('material-4/Editor/InsertLink')

' renders the element
InsertLink('InsertLink', 'Insert Link', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element InsertLink
include('material-4/Editor/InsertLink')

' renders the element
InsertLink('InsertLink', 'Insert Link', 'an optional tech label', 'an optional description')
@enduml
```

