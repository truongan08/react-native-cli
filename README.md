# react-native-cli
cai dat openjdk11
choco install -y nodejs-lts microsoft-openjdk11
cai dat android studio ( neu may yeu qua khong chay ADV duoc thi van cai lay tool chay may that )
set environment variable
ANDROID_HOME C:\Users\{user}\AppData\Local\Android\Sdk
Change my environment variables -> Path C:\Users\{user}\AppData\Local\Android\Sdk\platform-tools
chay lenh nay neu da cai react-native-cli npm uninstall -g react-native-cli @react-native-community/cli
npx react-native@latest init ProjectReact
cd ProjectReact
npx react-native start
- May that
  mo terminal su dung lenh adb devices de tim ten cua thiet bi va kiem tra da ket noi chua ( gan cap va bat debugging tren dien thoai , NHO BAT TRUYEN TEP)
  npx react-native run-android
- May ao
  Khong test tai may yeu co chay noi Android Studio dau

