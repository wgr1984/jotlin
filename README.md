# jotlin
Kotlin-ize java dev - An experiment to get as most Kotlin features to Java as possible

# Target
This repo shall be the last resort of all people bound to java (by Managment, Legacy or Love)
who still want to use similar cool feature as present in Kotlin and do not want to wait for java10 or above.

=> Our goal is to find alternatives or code your own stuff in order to achieve simal feature set than Kotlin

# Fatures
| Feature                   | State | Notes / Ideas     |
|---------------------------|-------|-------------------|
| Pattern-Matching          | tbd   |                   |
| Ranges                    | tbd   |                   |
| Data classes              | tbd   | extend auto-value |
| Default Mathod Parameters | tbd   | javadude/default  |
| Higher Order Func. / Lamdas | done | -> use retrolamba / RXjava2 |
| Null Safety               | 20%   | -> use Optionals (java 8 only / Android API 24) / Maybe(rxjava2) |
| "Real" Extension Methods  | tbd   | Thanks to project lombok already there but dueto Jetbrains IDEA still so far away :( |

## Android specific
| Feature                   | State | Notes / Ideas     |
|---------------------------|-------|-------------------|
| Export View Bindings      | 90%   | -> use DataBinding |
