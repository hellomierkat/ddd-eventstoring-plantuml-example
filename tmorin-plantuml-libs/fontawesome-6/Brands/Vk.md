# Vk


```text
fontawesome-6/Brands/Vk
```

```text
include('fontawesome-6/Brands/Vk')
```



| Illustration | Vk |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Vk.png) | ![illustration for Vk](../../fontawesome-6/Brands/Vk.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VkXs>`
- `<$VkSm>`
- `<$VkMd>`
- `<$VkLg>`





## Vk

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Vk
include('fontawesome-6/Brands/Vk')

' renders the element
Vk('Vk', 'Vk', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vk
include('fontawesome-6/Brands/Vk')

' renders the element
Vk('Vk', 'Vk', 'an optional tech label', 'an optional description')
@enduml
```

