# toy-story

## UI
* https://www.figma.com (fitnest UI)

## Setup
* https://velog.io/@jaeygun/MAC-OS-환경에서-Flutter-SDK-설치-및-환경변수-설정
* https://parkjh7764.tistory.com/171
* https://docs.flutter.dev/get-started/install

## Address
* Project: https://console.firebase.google.com/project/no-money-no-honey-okay/overview
* Backend: https://us-central1-no-money-no-honey-okay.cloudfunctions.net/api
* Frontend: https://no-money-no-honey-okay.web.app

## CLI
* flutter run
### Backend
```
npm install -g firebase-tools
firebase login
mkdir project
cd project
npm install cors
firebase init functions
flutter clean
flutter pub get
flutter upgrade
flutter build web
flutter run
firebase deploy --only functions
```


### Frontend
```
flutter config --enable-web
flutter build web
flutter run -d chrome
npm install -g firebase-tools
firebase login
firebase init
firebase deploy --only hosting
```
