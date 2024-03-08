# SentimentDissatisfied


```text
material-4/Social/SentimentDissatisfied
```

```text
include('material-4/Social/SentimentDissatisfied')
```



| Illustration | SentimentDissatisfied |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/SentimentDissatisfied.png) | ![illustration for SentimentDissatisfied](../../material-4/Social/SentimentDissatisfied.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SentimentDissatisfiedXs>`
- `<$SentimentDissatisfiedSm>`
- `<$SentimentDissatisfiedMd>`
- `<$SentimentDissatisfiedLg>`





## SentimentDissatisfied

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SentimentDissatisfied
include('material-4/Social/SentimentDissatisfied')

' renders the element
SentimentDissatisfied('SentimentDissatisfied', 'Sentiment Dissatisfied', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element SentimentDissatisfied
include('material-4/Social/SentimentDissatisfied')

' renders the element
SentimentDissatisfied('SentimentDissatisfied', 'Sentiment Dissatisfied', 'an optional tech label', 'an optional description')
@enduml
```

