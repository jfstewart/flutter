# flutter

Flutter learning...

Initial install on Windows:

Install: followed link	https://flutter.dev/docs/get-started/install/windows

Downloaded windows .zip: 
	https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.9.1+hotfix.4-stable.zip

Extract the zip file and place the contained flutter dir in the desired installation location for the 
Flutter SDK (for example, C:\src\flutter; 

mkdir src
unzip flutter.zip

upgrade path
run flutter doctor to test installation

Create github repository - flutter

echo "# flutter" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jfstewart/flutter.git
git push -u origin master

push files



To upgrade flutter: PS C:\src> flutter upgrade

To create a flutter app:
PS C:\src> cd jfs
PS C:\src\jfs> flutter create .

PS C:\src\jfs> flutter channel stable
Switching to flutter channel 'stable'...
git: From https://github.com/flutter/flutter
git:    89d6c8d90..6430b440d  master          -> origin/master
git:  + cc949a8e8...e70236e36 beta            -> origin/beta  (forced update)
git:  * [new branch]          dnfield-patch-1 -> origin/dnfield-patch-1
git: M  examples/hello_world/ios/Runner/GeneratedPluginRegistrant.h
git: M  examples/hello_world/ios/Runner/GeneratedPluginRegistrant.m
git: Your branch is up to date with 'origin/stable'.
git: Switched to branch 'stable'


To use flutter web app dev environment: change from stable to master

	flutter channel master
To enable WEB dev:
	PS C:\src> flutter config --enable-web
	Setting "enable-web" value to "true".

To run flugger web app:
flutter run -d chrome   
	example: PS C:\src\flutter\examples\hello_world> flutter run -d chrome
Storing jfs data: PS C:\src\jfs> flutter run -d chrome


Next need to download Android Studio
	https://developer.android.com/studio

