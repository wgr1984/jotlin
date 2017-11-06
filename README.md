# jotlin
Kotlin-ize java dev - An experiment to port most Kotlin features as possible to Java

# Target
This repo shall be the last resort of all people bound to java (by management, legacy or love)
who still want to use similar cool feature as present in Kotlin and do not want to wait for java10 or above.

=> Our goal is to find alternatives or code your own stuff in order to achieve similar feature set than Kotlin. May the annotionProcessor be with us :)

# Fatures
| Feature                   | State | Notes / Ideas     |
|---------------------------|-------|-------------------|
| Pattern-Matching          | tbd   |                   |
| Ranges                    | tbd   |                   |
| Data classes              | done   | [SimpleDataClassProcessor](https://github.com/wgr1984/SimpleDataClassProcessor) |
| Default Mathod Parameters | done   | [SimpleDefaultMethods](https://github.com/wgr1984/SimpleDefaultMethods)  |
| Higher Order Func. / Lamdas | done | -> use retrolamba / RXjava2 |
| Null Safety               | 20%   | -> use Optionals (java 8 only / Android API 24) / Maybe(rxjava2) |
| "Real" Extension Methods  | tbd   | Thanks to project lombok already there but dueto Jetbrains IDEA still so far away :( |

## Android specific
| Feature                   | State | Notes / Ideas     |
|---------------------------|-------|-------------------|
| Export View Bindings      | 90%   | -> use DataBinding |
