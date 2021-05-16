
### Get started logs
```
Microsoft Windows [Version 10.0.19042.985]
(c) Microsoft Corporation. All rights reserved.

C:\prj\flutterapp\win>git clone https://github.com/KK-MS/fwin.git
Cloning into 'fwin'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

C:\prj\flutterapp\win>cd fwin

C:\prj\flutterapp\win\fwin>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

C:\prj\flutterapp\win\fwin>s
's' is not recognized as an internal or external command,
operable program or batch file.

C:\prj\flutterapp\win\fwin>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

C:\prj\flutterapp\win\fwin>
C:\prj\flutterapp\win\fwin>dir
 Volume in drive C is Windows
 Volume Serial Number is BA13-5D5F

 Directory of C:\prj\flutterapp\win\fwin

05/16/2021  08:35 AM    <DIR>          .
05/16/2021  08:35 AM    <DIR>          ..
05/16/2021  08:35 AM    <DIR>          .vs
05/16/2021  08:35 AM                80 README.md
               1 File(s)             80 bytes
               3 Dir(s)  161,010,548,736 bytes free

C:\prj\flutterapp\win\fwin> flutter config --enable-<platform>-desktop
The system cannot find the file specified.

C:\prj\flutterapp\win\fwin>flutter --version
Flutter 2.0.4  channel stable  https://github.com/flutter/flutter.git
Framework  revision b1395592de (6 weeks ago)  2021-04-01 14:25:01 -0700
Engine  revision 2dce47073a
Tools  Dart 2.12.2

C:\prj\flutterapp\win\fwin>flutter config --enable-windows-desktop

C:\prj\flutterapp\win\fwin>cd code

C:\prj\flutterapp\win\fwin\code>flutter create fwinapp
Creating project fwinapp...
  fwinapp\.gitignore (created)
  fwinapp\.idea\libraries\Dart_SDK.xml (created)
  fwinapp\.idea\libraries\KotlinJavaRuntime.xml (created)
  fwinapp\.idea\modules.xml (created)
  fwinapp\.idea\runConfigurations\main_dart.xml (created)
  fwinapp\.idea\workspace.xml (created)
  fwinapp\.metadata (created)
  fwinapp\android\app\build.gradle (created)
  fwinapp\android\app\src\main\kotlin\com\example\fwinapp\MainActivity.kt (created)
  fwinapp\android\build.gradle (created)
  fwinapp\android\fwinapp_android.iml (created)
  fwinapp\android\.gitignore (created)
  fwinapp\android\app\src\debug\AndroidManifest.xml (created)
  fwinapp\android\app\src\main\AndroidManifest.xml (created)
  fwinapp\android\app\src\main\res\drawable\launch_background.xml (created)
  fwinapp\android\app\src\main\res\drawable-v21\launch_background.xml (created)
  fwinapp\android\app\src\main\res\mipmap-hdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-mdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xxhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xxxhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\values\styles.xml (created)
  fwinapp\android\app\src\main\res\values-night\styles.xml (created)
  fwinapp\android\app\src\profile\AndroidManifest.xml (created)
  fwinapp\android\gradle\wrapper\gradle-wrapper.properties (created)
  fwinapp\android\gradle.properties (created)
  fwinapp\android\settings.gradle (created)
  fwinapp\ios\Runner\AppDelegate.swift (created)
  fwinapp\ios\Runner\Runner-Bridging-Header.h (created)
  fwinapp\ios\Runner.xcodeproj\project.pbxproj (created)
  fwinapp\ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
  fwinapp\ios\.gitignore (created)
  fwinapp\ios\Flutter\AppFrameworkInfo.plist (created)
  fwinapp\ios\Flutter\Debug.xcconfig (created)
  fwinapp\ios\Flutter\Release.xcconfig (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-1024x1024@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-83.5x83.5@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\README.md (created)
  fwinapp\ios\Runner\Base.lproj\LaunchScreen.storyboard (created)
  fwinapp\ios\Runner\Base.lproj\Main.storyboard (created)
  fwinapp\ios\Runner\Info.plist (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  fwinapp\ios\Runner.xcworkspace\contents.xcworkspacedata (created)
  fwinapp\ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  fwinapp\ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  fwinapp\lib\main.dart (created)
  fwinapp\fwinapp.iml (created)
  fwinapp\pubspec.yaml (created)
  fwinapp\README.md (created)
  fwinapp\test\widget_test.dart (created)
  fwinapp\web\favicon.png (created)
  fwinapp\web\icons\Icon-192.png (created)
  fwinapp\web\icons\Icon-512.png (created)
  fwinapp\web\index.html (created)
  fwinapp\web\manifest.json (created)
Running "flutter pub get" in fwinapp...                          2,596ms
Wrote 78 files.

All done!
In order to run your application, type:

  $ cd fwinapp
  $ flutter run

To enable null safety, type:

  $ cd fwinapp
  $ dart migrate --apply-changes

Your application code is in fwinapp\lib\main.dart.


C:\prj\flutterapp\win\fwin\code>cd fwinapp

C:\prj\flutterapp\win\fwin\code\fwinapp>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

C:\prj\flutterapp\win\fwin\code\fwinapp>dir
 Volume in drive C is Windows
 Volume Serial Number is BA13-5D5F

 Directory of C:\prj\flutterapp\win\fwin\code\fwinapp

05/16/2021  08:37 AM    <DIR>          .
05/16/2021  08:37 AM    <DIR>          ..
05/16/2021  08:37 AM    <DIR>          .dart_tool
05/16/2021  08:37 AM               778 .gitignore
05/16/2021  08:37 AM    <DIR>          .idea
05/16/2021  08:37 AM               315 .metadata
05/16/2021  08:37 AM             2,129 .packages
05/16/2021  08:37 AM    <DIR>          android
05/16/2021  08:37 AM               913 fwinapp.iml
05/16/2021  08:37 AM    <DIR>          ios
05/16/2021  08:37 AM    <DIR>          lib
05/16/2021  08:37 AM             3,441 pubspec.lock
05/16/2021  08:37 AM             2,960 pubspec.yaml
05/16/2021  08:37 AM               553 README.md
05/16/2021  08:37 AM    <DIR>          test
05/16/2021  08:37 AM    <DIR>          web
               7 File(s)         11,089 bytes
               9 Dir(s)  160,987,549,696 bytes free

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter config --enable-windows-desktop
Setting "enable-windows-desktop" value to "true".

You may need to restart any open editors for them to read new settings.

C:\prj\flutterapp\win\fwin\code\fwinapp>cd ..

C:\prj\flutterapp\win\fwin\code>flutter create fwinapp
Creating project fwinapp...
  fwinapp\.gitignore (created)
  fwinapp\.idea\libraries\Dart_SDK.xml (created)
  fwinapp\.idea\libraries\KotlinJavaRuntime.xml (created)
  fwinapp\.idea\modules.xml (created)
  fwinapp\.idea\runConfigurations\main_dart.xml (created)
  fwinapp\.idea\workspace.xml (created)
  fwinapp\.metadata (created)
  fwinapp\android\app\build.gradle (created)
  fwinapp\android\app\src\main\kotlin\com\example\fwinapp\MainActivity.kt (created)
  fwinapp\android\build.gradle (created)
  fwinapp\android\fwinapp_android.iml (created)
  fwinapp\android\.gitignore (created)
  fwinapp\android\app\src\debug\AndroidManifest.xml (created)
  fwinapp\android\app\src\main\AndroidManifest.xml (created)
  fwinapp\android\app\src\main\res\drawable\launch_background.xml (created)
  fwinapp\android\app\src\main\res\drawable-v21\launch_background.xml (created)
  fwinapp\android\app\src\main\res\mipmap-hdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-mdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xxhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\mipmap-xxxhdpi\ic_launcher.png (created)
  fwinapp\android\app\src\main\res\values\styles.xml (created)
  fwinapp\android\app\src\main\res\values-night\styles.xml (created)
  fwinapp\android\app\src\profile\AndroidManifest.xml (created)
  fwinapp\android\gradle\wrapper\gradle-wrapper.properties (created)
  fwinapp\android\gradle.properties (created)
  fwinapp\android\settings.gradle (created)
  fwinapp\ios\Runner\AppDelegate.swift (created)
  fwinapp\ios\Runner\Runner-Bridging-Header.h (created)
  fwinapp\ios\Runner.xcodeproj\project.pbxproj (created)
  fwinapp\ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
  fwinapp\ios\.gitignore (created)
  fwinapp\ios\Flutter\AppFrameworkInfo.plist (created)
  fwinapp\ios\Flutter\Debug.xcconfig (created)
  fwinapp\ios\Flutter\Release.xcconfig (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-1024x1024@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@1x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-83.5x83.5@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@2x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@3x.png (created)
  fwinapp\ios\Runner\Assets.xcassets\LaunchImage.imageset\README.md (created)
  fwinapp\ios\Runner\Base.lproj\LaunchScreen.storyboard (created)
  fwinapp\ios\Runner\Base.lproj\Main.storyboard (created)
  fwinapp\ios\Runner\Info.plist (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  fwinapp\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  fwinapp\ios\Runner.xcworkspace\contents.xcworkspacedata (created)
  fwinapp\ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  fwinapp\ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  fwinapp\lib\main.dart (created)
  fwinapp\fwinapp.iml (created)
  fwinapp\pubspec.yaml (created)
  fwinapp\README.md (created)
  fwinapp\test\widget_test.dart (created)
  fwinapp\web\favicon.png (created)
  fwinapp\web\icons\Icon-192.png (created)
  fwinapp\web\icons\Icon-512.png (created)
  fwinapp\web\index.html (created)
  fwinapp\web\manifest.json (created)
  fwinapp\windows\.gitignore (created)
  fwinapp\windows\CMakeLists.txt (created)
  fwinapp\windows\flutter\CMakeLists.txt (created)
  fwinapp\windows\runner\CMakeLists.txt (created)
  fwinapp\windows\runner\flutter_window.cpp (created)
  fwinapp\windows\runner\flutter_window.h (created)
  fwinapp\windows\runner\main.cpp (created)
  fwinapp\windows\runner\resource.h (created)
  fwinapp\windows\runner\resources\app_icon.ico (created)
  fwinapp\windows\runner\runner.exe.manifest (created)
  fwinapp\windows\runner\Runner.rc (created)
  fwinapp\windows\runner\run_loop.cpp (created)
  fwinapp\windows\runner\run_loop.h (created)
  fwinapp\windows\runner\utils.cpp (created)
  fwinapp\windows\runner\utils.h (created)
  fwinapp\windows\runner\win32_window.cpp (created)
  fwinapp\windows\runner\win32_window.h (created)
Running "flutter pub get" in fwinapp...                          1,804ms
Wrote 95 files.

All done!
In order to run your application, type:

  $ cd fwinapp
  $ flutter run

To enable null safety, type:

  $ cd fwinapp
  $ dart migrate --apply-changes

Your application code is in fwinapp\lib\main.dart.


C:\prj\flutterapp\win\fwin\code>cd fwinapp

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter config --enable-windows-desktop
Setting "enable-windows-desktop" value to "true".

You may need to restart any open editors for them to read new settings.

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter devices
3 connected devices:

Windows (desktop)  windows  windows-x64     Microsoft Windows [Version 10.0.19042.985]
Chrome (web)       chrome   web-javascript  Google Chrome 90.0.4430.212
Edge (web)         edge     web-javascript  Microsoft Edge 90.0.818.62

C:\prj\flutterapp\win\fwin\code\fwinapp>flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[v] Flutter (Channel stable, 2.0.4, on Microsoft Windows [Version 10.0.19042.985], locale en-US)
[v] Android toolchain - develop for Android devices (Android SDK version 30.0.3)
[v] Chrome - develop for the web
[v] Visual Studio - develop for Windows (Visual Studio Community 2019 16.9.5)
[v] Android Studio (version 4.1.0)
[v] Connected device (3 available)

 No issues found!

C:\prj\flutterapp\win\fwin\code\fwinapp>
```