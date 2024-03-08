# Wish


```text
simpleicons-8/W/Wish
```

```text
include('simpleicons-8/W/Wish')
```



| Illustration | Wish |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/W/Wish.png) | ![illustration for Wish](../../simpleicons-8/W/Wish.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WishXs>`
- `<$WishSm>`
- `<$WishMd>`
- `<$WishLg>`





## Wish

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Wish
include('simpleicons-8/W/Wish')

' renders the element
Wish('Wish', 'Wish', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wish
include('simpleicons-8/W/Wish')

' renders the element
Wish('Wish', 'Wish', 'an optional tech label', 'an optional description')
@enduml
```

