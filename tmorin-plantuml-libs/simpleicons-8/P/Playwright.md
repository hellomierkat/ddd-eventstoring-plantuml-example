# Playwright


```text
simpleicons-8/P/Playwright
```

```text
include('simpleicons-8/P/Playwright')
```



| Illustration | Playwright |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/P/Playwright.png) | ![illustration for Playwright](../../simpleicons-8/P/Playwright.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PlaywrightXs>`
- `<$PlaywrightSm>`
- `<$PlaywrightMd>`
- `<$PlaywrightLg>`





## Playwright

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Playwright
include('simpleicons-8/P/Playwright')

' renders the element
Playwright('Playwright', 'Playwright', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Playwright
include('simpleicons-8/P/Playwright')

' renders the element
Playwright('Playwright', 'Playwright', 'an optional tech label', 'an optional description')
@enduml
```

