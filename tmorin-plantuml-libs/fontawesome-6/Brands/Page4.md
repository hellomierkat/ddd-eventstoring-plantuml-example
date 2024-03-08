# Page4


```text
fontawesome-6/Brands/Page4
```

```text
include('fontawesome-6/Brands/Page4')
```



| Illustration | Page4 |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Page4.png) | ![illustration for Page4](../../fontawesome-6/Brands/Page4.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Page4Xs>`
- `<$Page4Sm>`
- `<$Page4Md>`
- `<$Page4Lg>`





## Page4

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Page4
include('fontawesome-6/Brands/Page4')

' renders the element
Page4('Page4', 'Page4', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Page4
include('fontawesome-6/Brands/Page4')

' renders the element
Page4('Page4', 'Page4', 'an optional tech label', 'an optional description')
@enduml
```

