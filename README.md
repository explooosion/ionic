# Angular with ionic
+安裝vs20105
+更新Android SDK(platform)
+安裝nodejs


#安裝指令
```
npm install -g ionic
```

#建立方案
```
ionic start myApp tabs
```

```
cd myApp
ionic platform add android
```

```
ionic build android
```

環境變數
ANDROID_HOME=D:\Android\sdk
JAVA_HOME=C:\Program Files (x86)\Java\jdk1.7.0_55

path：%ANDROID_HOME%;%JAVA_HOME%\bin;


執行
```
ionic run android
ionic serve
```

