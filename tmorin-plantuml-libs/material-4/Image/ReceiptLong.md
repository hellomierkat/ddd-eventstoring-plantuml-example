# ReceiptLong


```text
material-4/Image/ReceiptLong
```

```text
include('material-4/Image/ReceiptLong')
```



| Illustration | ReceiptLong |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/ReceiptLong.png) | ![illustration for ReceiptLong](../../material-4/Image/ReceiptLong.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReceiptLongXs>`
- `<$ReceiptLongSm>`
- `<$ReceiptLongMd>`
- `<$ReceiptLongLg>`





## ReceiptLong

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ReceiptLong
include('material-4/Image/ReceiptLong')

' renders the element
ReceiptLong('ReceiptLong', 'Receipt Long', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ReceiptLong
include('material-4/Image/ReceiptLong')

' renders the element
ReceiptLong('ReceiptLong', 'Receipt Long', 'an optional tech label', 'an optional description')
@enduml
```

