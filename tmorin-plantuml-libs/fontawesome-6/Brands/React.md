# React


```text
fontawesome-6/Brands/React
```

```text
include('fontawesome-6/Brands/React')
```



| Illustration | React |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/React.png) | ![illustration for React](../../fontawesome-6/Brands/React.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReactXs>`
- `<$ReactSm>`
- `<$ReactMd>`
- `<$ReactLg>`





## React

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element React
include('fontawesome-6/Brands/React')

' renders the element
React('React', 'React', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element React
include('fontawesome-6/Brands/React')

' renders the element
React('React', 'React', 'an optional tech label', 'an optional description')
@enduml
```

