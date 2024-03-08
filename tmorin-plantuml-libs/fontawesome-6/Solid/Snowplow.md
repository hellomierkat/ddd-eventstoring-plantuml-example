# Snowplow


```text
fontawesome-6/Solid/Snowplow
```

```text
include('fontawesome-6/Solid/Snowplow')
```



| Illustration | Snowplow |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Snowplow.png) | ![illustration for Snowplow](../../fontawesome-6/Solid/Snowplow.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SnowplowXs>`
- `<$SnowplowSm>`
- `<$SnowplowMd>`
- `<$SnowplowLg>`





## Snowplow

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Snowplow
include('fontawesome-6/Solid/Snowplow')

' renders the element
Snowplow('Snowplow', 'Snowplow', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Snowplow
include('fontawesome-6/Solid/Snowplow')

' renders the element
Snowplow('Snowplow', 'Snowplow', 'an optional tech label', 'an optional description')
@enduml
```

