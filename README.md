# bbdb-android - Android phone contacts import/export for BBDB

*Author:* Feng Shu <tumashu@163.com><br>
*Version:* 0.0.1<br>

### Introduce ###

bbdb-android is a BBDB v3 tool, which can import and export from/to
android phone contacts database to/from BBDB (The Insidious Big Brother Database).

NOTE: You need make sure your android phone *rooted*.

### Download ###

    https://github.com/tumashu/bbdb-android

### Install ###

1. Install adb and sqlite3.
2. Config melpa: http://melpa.org/#/getting-started
2. M-x package-install RET bbdb-android RET
3. Add code to your emacs config file:（for example: ~/.emacs）：

```lisp
(require 'bbdb-android)
```

### Usage ###

Import contacts to BBDB from android phone

```lisp
M-x bbdb-android-import RET
```

Export contacts to android phone from BBDB

```lisp
M-x bbdb-android-export RET
```

### Issues ###

1. adb and sqlite3 commands is hard-code,
   make sure add them to system PATH.
2. When multi android devices are connected,
   bbdb-android can't work properly.


---
Converted from `bbdb-android.el` by [*el2markdown*](https://github.com/Lindydancer/el2markdown).
