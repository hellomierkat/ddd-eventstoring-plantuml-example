# Googlehome


```text
simpleicons-8/G/Googlehome
```

```text
include('simpleicons-8/G/Googlehome')
```



| Illustration | Googlehome |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Googlehome.png) | ![illustration for Googlehome](../../simpleicons-8/G/Googlehome.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GooglehomeXs>`
- `<$GooglehomeSm>`
- `<$GooglehomeMd>`
- `<$GooglehomeLg>`





## Googlehome

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Googlehome
include('simpleicons-8/G/Googlehome')

' renders the element
Googlehome('Googlehome', 'Googlehome', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Googlehome
include('simpleicons-8/G/Googlehome')

' renders the element
Googlehome('Googlehome', 'Googlehome', 'an optional tech label', 'an optional description')
@enduml
```

