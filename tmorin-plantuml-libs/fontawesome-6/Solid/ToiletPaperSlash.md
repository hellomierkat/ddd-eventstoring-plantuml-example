# ToiletPaperSlash


```text
fontawesome-6/Solid/ToiletPaperSlash
```

```text
include('fontawesome-6/Solid/ToiletPaperSlash')
```



| Illustration | ToiletPaperSlash |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/ToiletPaperSlash.png) | ![illustration for ToiletPaperSlash](../../fontawesome-6/Solid/ToiletPaperSlash.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ToiletPaperSlashXs>`
- `<$ToiletPaperSlashSm>`
- `<$ToiletPaperSlashMd>`
- `<$ToiletPaperSlashLg>`





## ToiletPaperSlash

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element ToiletPaperSlash
include('fontawesome-6/Solid/ToiletPaperSlash')

' renders the element
ToiletPaperSlash('ToiletPaperSlash', 'Toilet Paper Slash', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ToiletPaperSlash
include('fontawesome-6/Solid/ToiletPaperSlash')

' renders the element
ToiletPaperSlash('ToiletPaperSlash', 'Toilet Paper Slash', 'an optional tech label', 'an optional description')
@enduml
```

