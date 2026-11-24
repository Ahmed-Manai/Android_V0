# Android_V0

An early Android prototype in Java (package `fst.ahmed.h96_tn_robot`) to try out fragment-based navigation with the Android Navigation component.

## What's in it

- `MainActivity` with a toolbar and a navigation host
- `FirstFragment` and `SecondFragment`, connected by actions in `res/navigation/nav_graph.xml`
- A `ThirdFragment` that was being added when the prototype stopped

Built with AndroidX AppCompat, Material Components, ConstraintLayout and Navigation 2.0, for Android 6.0+ (minSdk 23, targetSdk 28).

## Status

This is an unfinished prototype and doesn't build as it is: the second button in `FirstFragment` still has an incomplete navigation action (`navigate(R.id.)`). It's kept as a record of learning the Navigation component.
