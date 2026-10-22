---
'expo-modules-jsi': patch
---

[iOS] Make `JavaScriptObject.takeValue()` public. It moves an object into a `JavaScriptValue` without the copy that `asValue()` makes.
