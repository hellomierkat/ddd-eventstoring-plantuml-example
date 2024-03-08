# FaceKissWinkHeart


```text
fontawesome-6/Regular/FaceKissWinkHeart
```

```text
include('fontawesome-6/Regular/FaceKissWinkHeart')
```



| Illustration | FaceKissWinkHeart |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Regular/FaceKissWinkHeart.png) | ![illustration for FaceKissWinkHeart](../../fontawesome-6/Regular/FaceKissWinkHeart.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FaceKissWinkHeartXs>`
- `<$FaceKissWinkHeartSm>`
- `<$FaceKissWinkHeartMd>`
- `<$FaceKissWinkHeartLg>`





## FaceKissWinkHeart

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FaceKissWinkHeart
include('fontawesome-6/Regular/FaceKissWinkHeart')

' renders the element
FaceKissWinkHeart('FaceKissWinkHeart', 'Face Kiss Wink Heart', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FaceKissWinkHeart
include('fontawesome-6/Regular/FaceKissWinkHeart')

' renders the element
FaceKissWinkHeart('FaceKissWinkHeart', 'Face Kiss Wink Heart', 'an optional tech label', 'an optional description')
@enduml
```

