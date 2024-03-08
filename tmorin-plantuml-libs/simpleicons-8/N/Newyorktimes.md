# Newyorktimes


```text
simpleicons-8/N/Newyorktimes
```

```text
include('simpleicons-8/N/Newyorktimes')
```



| Illustration | Newyorktimes |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/N/Newyorktimes.png) | ![illustration for Newyorktimes](../../simpleicons-8/N/Newyorktimes.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$NewyorktimesXs>`
- `<$NewyorktimesSm>`
- `<$NewyorktimesMd>`
- `<$NewyorktimesLg>`





## Newyorktimes

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Newyorktimes
include('simpleicons-8/N/Newyorktimes')

' renders the element
Newyorktimes('Newyorktimes', 'Newyorktimes', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Newyorktimes
include('simpleicons-8/N/Newyorktimes')

' renders the element
Newyorktimes('Newyorktimes', 'Newyorktimes', 'an optional tech label', 'an optional description')
@enduml
```

