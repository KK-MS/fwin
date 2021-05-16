

# Main.

main.dart:

1. null check added:

* line 74: Added a non-null assertion to nullable expression

  `title: Text(widget.title) =>  title: Text(widget.title!)`
  
2. types made nullable:

* line 31: Changed type 'Key' to be nullable
  `MyHomePage({Key key, this.title}) : super(key: key)`  
  `MyHomePage({Key? key, this.title}) : super(key: key)`  
  
* line 42: Changed type 'String' to be nullable
  `final String title;`
  `final String? title;`
  
## Pubspec.yaml

Changed sdk version:
```
environment:
  sdk: ">=2.7.0 <3.0.0
```
to
```
sdk: '>=2.12.0 <3.0.0'
```

## Command logs:

Microsoft Windows [Version 10.0.19042.985]
(c) Microsoft Corporation. All rights reserved.

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter build windows

Building without sound null safety
For more information see https://dart.dev/null-safety/unsound-null-safety

Building Windows application...

C:\prj\flutterapp\win\fwin\code\fwinapp> dart pub outdated --mode=null-safety
Resolving...
Showing dependencies that are currently not opted in to null-safety.
[✗] indicates versions without null safety support.
[✓] indicates versions opting in to null safety.

Computing null safety support...
All your dependencies declare support for null-safety.

C:\prj\flutterapp\win\fwin\code\fwinapp>dart pub upgrade --null-safety
Resolving dependencies...
Resolving dependencies...
  async 2.5.0 (2.6.1 available)
  boolean_selector 2.1.0
  characters 1.1.0      
  charcode 1.2.0        
  clock 1.1.0
  collection 1.15.0     
  cupertino_icons 1.0.3 
  fake_async 1.2.0      
  ffi 1.0.0
  file 6.1.0
  flutter 0.0.0 from sdk flutter
  flutter_test 0.0.0 from sdk flutter
  matcher 0.12.10
  meta 1.3.0
  path 1.8.0
  path_provider 2.0.1
  path_provider_linux 2.0.0
  path_provider_macos 2.0.0
  path_provider_platform_interface 2.0.1
  path_provider_windows 2.0.1
  platform 3.0.0
  plugin_platform_interface 2.0.0
  process 4.2.1
  sky_engine 0.0.99 from sdk flutter
  source_span 1.8.0 (1.8.1 available)
  stack_trace 1.10.0
  stream_channel 2.1.0
  string_scanner 1.1.0
  term_glyph 1.2.0
  test_api 0.2.19 (0.4.0 available)
  typed_data 1.3.0
  vector_math 2.1.0
  win32 2.0.5
  xdg_directories 0.2.0
Downloading path_provider 2.0.1...
Downloading cupertino_icons 1.0.3...
Downloading path_provider_macos 2.0.0...
Downloading path_provider_linux 2.0.0...
Downloading xdg_directories 0.2.0...
Downloading path_provider_windows 2.0.1...
Downloading ffi 1.0.0...
Downloading path_provider_platform_interface 2.0.1...
Downloading plugin_platform_interface 2.0.0...
Downloading platform 3.0.0...
Downloading process 4.2.1...
Downloading file 6.1.0...
Downloading win32 2.0.5...
No dependencies changed.
3 packages have newer versions incompatible with dependency constraints.
Try `dart pub outdated` for more information.

Changed 1 constraint in pubspec.yaml:
  cupertino_icons: ^1.0.2 -> ^1.0.3

C:\prj\flutterapp\win\fwin\code\fwinapp> dart pub outdated --mode=null-safety

C:\prj\flutterapp\win\fwin\code\fwinapp>dart pub get
Resolving dependencies...
  async 2.5.0 (2.6.1 available)
  source_span 1.8.0 (1.8.1 available)
  test_api 0.2.19 (0.4.0 available)
Got dependencies!

C:\prj\flutterapp\win\fwin\code\fwinapp>dart migrate
Migrating C:\prj\flutterapp\win\fwin\code\fwinapp

See https://dart.dev/go/null-safety-migration for a migration guide.

Analyzing project...
[----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|]No analysis issues found.

Generating migration suggestions...
[-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------]
Compiling instrumentation information...
[-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------]
View the migration suggestions by visiting:

  http://127.0.0.1:51990/C:/prj/flutterapp/win/fwin/code/fwinapp?authToken=UKD6J-z666k%3D

Use this interactive web view to review, improve, or apply the results.
When finished with the preview, hit ctrl-c to terminate this process.

If you make edits outside of the web view (in your IDE), use the 'Rerun from
sources' action.


Applying migration suggestions to disk...
Migrated 4 files:
    lib\main.dart
    test\widget_test.dart
    pubspec.yaml
    .dart_tool\package_config.json

C:\prj\flutterapp\win\fwin\code\fwinapp>
C:\prj\flutterapp\win\fwin\code\fwinapp>
C:\prj\flutterapp\win\fwin\code\fwinapp>
C:\prj\flutterapp\win\fwin\code\fwinapp>
C:\prj\flutterapp\win\fwin\code\fwinapp>flutter build windows

 Building with sound null safety 

Building with plugins requires symlink support.

Please enable Developer Mode in your system settings. Run
  start ms-settings:developers
to open settings.

C:\prj\flutterapp\win\fwin\code\fwinapp>start ms-settings:developers

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter build windows        

 Building with sound null safety 

Building with plugins requires symlink support.

Please enable Developer Mode in your system settings. Run
  start ms-settings:developers
to open settings.

C:\prj\flutterapp\win\fwin\code\fwinapp>git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/ins/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=false
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
user.email=kk.contact.mail@gmail.com
user.name=KK-MS
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/KK-MS/fwin.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
:...skipping...
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/ins/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=false
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
user.email=kk.contact.mail@gmail.com
user.name=KK-MS
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/KK-MS/fwin.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
~
~
~
~
~
~
~
~
~
~
~
~
~

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter build windows        

 Building with sound null safety 

Building with plugins requires symlink support.

Please enable Developer Mode in your system settings. Run
  start ms-settings:developers
to open settings.

https://github.com/flutter/flutter/issues/72462

=> stevenovack commented on Dec 19, 2020  
@TahaTesser Setting core.symlinks=true had no effect.

But, after digging a bit deeper, it looks like I don't have the permission needed to create Windows symlinks, even though Developer Mode is enabled (apparently "ln -s", which does work, isn't implemented using Windows symlinks).

I may eventually be able to get Windows symlinks enabled on this machine, but I'm wondering if you can suggest any workarounds? Or, would it be easy to change my local Flutter implementation to not need Windows symlinks?

=> TahaTesser commented on Dec 21, 2020  
Hi @stevenovack
That might be it, hope you enable it and get it working on your system. I tried to find a workaround by disabling developer mode but I couldn't find any workaround. If you find any, comment below, it would help others.
Given your last message I feel safe to close this issue, if you disagree please write in the comments and I will reopen it.
Thank you

### Conclusion.

I also dont have permission for now, thus dont enable null-safety

Revert:
environment:
  sdk: '>=2.12.0 <3.0.0'
  
Commands:
```
 dart --no-sound-null-safety run
 flutter run --no-sound-null-safety
```

Logs:
```

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter build windows        

 Building with sound null safety 

Building with plugins requires symlink support.

Please enable Developer Mode in your system settings. Run
  start ms-settings:developers
to open settings.

C:\prj\flutterapp\win\fwin\code\fwinapp> 
C:\prj\flutterapp\win\fwin\code\fwinapp>
C:\prj\flutterapp\win\fwin\code\fwinapp> dart --no-sound-null-safety run
Could not find `bin\fwinapp.dart` in package `fwinapp`.

C:\prj\flutterapp\win\fwin\code\fwinapp> flutter run --no-sound-null-safety
Multiple devices found:
Windows (desktop) • windows • windows-x64    • Microsoft Windows [Version 10.0.19042.985]
Chrome (web)      • chrome  • web-javascript • Google Chrome 90.0.4430.212
Edge (web)        • edge    • web-javascript • Microsoft Edge 90.0.818.62
[1]: Windows (windows)
[2]: Chrome (chrome)
[3]: Edge (edge)
Please choose one (To quit, press "q/Q"): 1
Launching lib\main.dart on Windows in debug mode...
Exception: Building with plugins requires symlink support.

Please enable Developer Mode in your system settings. Run
  start ms-settings:developers
to open settings.

```