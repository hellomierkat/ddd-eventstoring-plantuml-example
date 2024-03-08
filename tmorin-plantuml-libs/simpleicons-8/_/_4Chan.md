# _4Chan


```text
simpleicons-8/_/_4Chan
```

```text
include('simpleicons-8/_/_4Chan')
```



| Illustration | _4Chan |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/_/_4Chan.png) | ![illustration for _4Chan](../../simpleicons-8/_/_4Chan.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$_4ChanXs>`
- `<$_4ChanSm>`
- `<$_4ChanMd>`
- `<$_4ChanLg>`





## _4Chan

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element _4Chan
include('simpleicons-8/_/_4Chan')

' renders the element
_4Chan('4chan', '4chan', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element _4Chan
include('simpleicons-8/_/_4Chan')

' renders the element
_4Chan('4chan', '4chan', 'an optional tech label', 'an optional description')
@enduml
```

