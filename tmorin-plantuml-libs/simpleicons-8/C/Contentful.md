# Contentful


```text
simpleicons-8/C/Contentful
```

```text
include('simpleicons-8/C/Contentful')
```



| Illustration | Contentful |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Contentful.png) | ![illustration for Contentful](../../simpleicons-8/C/Contentful.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ContentfulXs>`
- `<$ContentfulSm>`
- `<$ContentfulMd>`
- `<$ContentfulLg>`





## Contentful

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Contentful
include('simpleicons-8/C/Contentful')

' renders the element
Contentful('Contentful', 'Contentful', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Contentful
include('simpleicons-8/C/Contentful')

' renders the element
Contentful('Contentful', 'Contentful', 'an optional tech label', 'an optional description')
@enduml
```

