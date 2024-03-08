# Flipkart


```text
simpleicons-8/F/Flipkart
```

```text
include('simpleicons-8/F/Flipkart')
```



| Illustration | Flipkart |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/F/Flipkart.png) | ![illustration for Flipkart](../../simpleicons-8/F/Flipkart.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FlipkartXs>`
- `<$FlipkartSm>`
- `<$FlipkartMd>`
- `<$FlipkartLg>`





## Flipkart

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Flipkart
include('simpleicons-8/F/Flipkart')

' renders the element
Flipkart('Flipkart', 'Flipkart', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Flipkart
include('simpleicons-8/F/Flipkart')

' renders the element
Flipkart('Flipkart', 'Flipkart', 'an optional tech label', 'an optional description')
@enduml
```

