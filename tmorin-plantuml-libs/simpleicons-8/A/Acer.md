# Acer


```text
simpleicons-8/A/Acer
```

```text
include('simpleicons-8/A/Acer')
```



| Illustration | Acer |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Acer.png) | ![illustration for Acer](../../simpleicons-8/A/Acer.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AcerXs>`
- `<$AcerSm>`
- `<$AcerMd>`
- `<$AcerLg>`





## Acer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Acer
include('simpleicons-8/A/Acer')

' renders the element
Acer('Acer', 'Acer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Acer
include('simpleicons-8/A/Acer')

' renders the element
Acer('Acer', 'Acer', 'an optional tech label', 'an optional description')
@enduml
```

