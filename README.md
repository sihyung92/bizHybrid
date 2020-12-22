### 환경설정
[https://cordova.apache.org/#getstarted](https://cordova.apache.org/#getstarted)

1. npm install -g cordova
2. gradle 설치 [https://gradle.org/install/](https://gradle.org/install/)
3. gradle 환경변수 등록
    1. gradle  daemon heaps size오류(기본 2g)가 나면 시스템 변수에 GRADLE_OPTS 에 `Dorg.gradle.jvmargs=-Xmx1g` 등록
4. andoid studio 설치
    1. ANDROID_SDK_ROOT  환경변수 추가
    2. AVD manager에서 android api 29버전 설치 

### 실행

1. cordova create MyApp
2. cd myapp
3. cordova platform add android
4. cordova platform add webbrowser
5. cordova platform add 
6. 안드로이드 실행 
    1. cordova run —emulator 
    2. cordova run android
7. 웹 실행
    1. cordova run webbrowser