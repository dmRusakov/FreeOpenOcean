flutter create app
cd app
flutter config --enable-web
flutter config --enable-linux-desktop
flutter config --enable-windows-desktop
flutter config --enable-ios
flutter run -d chrome
flutter run -d linux
flutter run -d windows
flutter run -d emulator-id
flutter run -d "iPhone 14"
flutter build web
flutter build linux
flutter build windows
flutter build apk
flutter build ios --release --no-codesign