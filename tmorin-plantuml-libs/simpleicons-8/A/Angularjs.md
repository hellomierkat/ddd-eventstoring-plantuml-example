# Angularjs


```text
simpleicons-8/A/Angularjs
```

```text
include('simpleicons-8/A/Angularjs')
```



| Illustration | Angularjs |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Angularjs.png) | ![illustration for Angularjs](../../simpleicons-8/A/Angularjs.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AngularjsXs>`
- `<$AngularjsSm>`
- `<$AngularjsMd>`
- `<$AngularjsLg>`





## Angularjs

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Angularjs
include('simpleicons-8/A/Angularjs')

' renders the element
Angularjs('Angularjs', 'Angularjs', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Angularjs
include('simpleicons-8/A/Angularjs')

' renders the element
Angularjs('Angularjs', 'Angularjs', 'an optional tech label', 'an optional description')
@enduml
```

