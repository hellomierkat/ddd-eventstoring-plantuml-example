# CreativeCommonsSampling


```text
fontawesome-6/Brands/CreativeCommonsSampling
```

```text
include('fontawesome-6/Brands/CreativeCommonsSampling')
```



| Illustration | CreativeCommonsSampling |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/CreativeCommonsSampling.png) | ![illustration for CreativeCommonsSampling](../../fontawesome-6/Brands/CreativeCommonsSampling.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CreativeCommonsSamplingXs>`
- `<$CreativeCommonsSamplingSm>`
- `<$CreativeCommonsSamplingMd>`
- `<$CreativeCommonsSamplingLg>`





## CreativeCommonsSampling

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CreativeCommonsSampling
include('fontawesome-6/Brands/CreativeCommonsSampling')

' renders the element
CreativeCommonsSampling('CreativeCommonsSampling', 'Creative Commons Sampling', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CreativeCommonsSampling
include('fontawesome-6/Brands/CreativeCommonsSampling')

' renders the element
CreativeCommonsSampling('CreativeCommonsSampling', 'Creative Commons Sampling', 'an optional tech label', 'an optional description')
@enduml
```

