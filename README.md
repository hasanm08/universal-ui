### Universal UI
Temporary fix for dart: ui

### Getting Started
This plugin is a temporary fix for the dart: ui issue.

Some of the issues thread:
https://github.com/flutter/flutter/issues/41563
https://github.com/flutter/flutter/issues/43166


This solution was not my idea.
I just published it in pub.dev to make it easier to implement.

If you want me to credit this solution,
please mail me at flutterlabz@gmail.com.

Because I don't know who suggested it first.
I hope this plugin can help those who are experiencing the same problem.

### How To Use
Import the package.
```
import 'package:universal_ui/universal_ui.dart';
```

Then, use the ui object as usual. 
You don't need to create an alias and add ignore:

```
...
ui.platformViewRegistry.registerViewFactory(
    'iframeElement',
    (int viewId) => _iframeElement,
);
...

```
"# universa-ui" 
