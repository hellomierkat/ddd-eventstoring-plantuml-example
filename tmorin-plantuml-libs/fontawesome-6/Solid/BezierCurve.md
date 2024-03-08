# BezierCurve


```text
fontawesome-6/Solid/BezierCurve
```

```text
include('fontawesome-6/Solid/BezierCurve')
```



| Illustration | BezierCurve |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BezierCurve.png) | ![illustration for BezierCurve](../../fontawesome-6/Solid/BezierCurve.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$BezierCurveXs>`
- `<$BezierCurveSm>`
- `<$BezierCurveMd>`
- `<$BezierCurveLg>`





## BezierCurve

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BezierCurve
include('fontawesome-6/Solid/BezierCurve')

' renders the element
BezierCurve('BezierCurve', 'Bezier Curve', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BezierCurve
include('fontawesome-6/Solid/BezierCurve')

' renders the element
BezierCurve('BezierCurve', 'Bezier Curve', 'an optional tech label', 'an optional description')
@enduml
```

