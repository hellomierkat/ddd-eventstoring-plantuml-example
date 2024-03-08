# Autoprefixer


```text
simpleicons-8/A/Autoprefixer
```

```text
include('simpleicons-8/A/Autoprefixer')
```



| Illustration | Autoprefixer |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Autoprefixer.png) | ![illustration for Autoprefixer](../../simpleicons-8/A/Autoprefixer.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AutoprefixerXs>`
- `<$AutoprefixerSm>`
- `<$AutoprefixerMd>`
- `<$AutoprefixerLg>`





## Autoprefixer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Autoprefixer
include('simpleicons-8/A/Autoprefixer')

' renders the element
Autoprefixer('Autoprefixer', 'Autoprefixer', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Autoprefixer
include('simpleicons-8/A/Autoprefixer')

' renders the element
Autoprefixer('Autoprefixer', 'Autoprefixer', 'an optional tech label', 'an optional description')
@enduml
```

