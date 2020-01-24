[![Codemagic build status](https://api.codemagic.io/apps/5e2a1ba1cc644b00105fe31d/5e2a1ba1cc644b00105fe31c/status_badge.svg)](https://codemagic.io/apps/5e2a1ba1cc644b00105fe31d/5e2a1ba1cc644b00105fe31c/latest_build)

# roller_list package
This widget is a list of values distributed in a circle. The main rules of the list are: a user could scroll it in one direction endlessly, list values are limited and repeated in the same order over and over again.
Possible usage scheme:
-time selection
-piano notes selection
-choice of any limited number of items, where it is not important what should go first and what should go last.

## Example
You can check Flutter for web build [here](https://opensource.0x.team/roller-list/demo/index.html#/)
Or see how it looks like on iphone:
![](iphone_screen.gif)

## How to use
In the dependencies: section of your pubspec.yaml, add the following line:
```dart
roller_list: <latest version>
```

Then import this class:
```dart
import 'package:roller_list/roller_list.dart';
```

And add your list like this: 
```dart
RollerList(
 items: slots,
 enabled: false,
 key: leftRoller,
)
```
