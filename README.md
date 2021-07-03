# realbizgames-unity-common-init-chain

![The product concept](Images~/Lego_Concept.jpeg)

# The Concept
1. Games contain many of the same reusable components.
2. Build these "the same reusable components" into many simple, stable, scalable smaller projects.
3. Combine them to make a big game project.


Let's start from NOW or NEVER.
  
# Inhouse Components


## Unity Purchasing

```
"com.unity.purchasing": "3.2.1",
```

## RealbizGames Data
https://github.com/truonguit2010/realbizgames-data/tree/main
```
"com.realbizgames.data": "https://github.com/truonguit2010/realbizgames-data.git#v1.0.0",
```

## Banner Ad Settings

```
https://github.com/truonguit2010/realbizgames-banner-ads-setting
```

# 3rd Party Components
#### 1. Facebook SDK
- https://developers.facebook.com/docs/unity/
#### 2. Firebase
We use:
- Firebase Analytics
- Google Analytics
- Firebase Remote Config
- Firebase Cloud Messaging

Download these packages at https://developers.google.com/unity/archive

```
"com.google.external-dependency-manager": "file:../Tarballs/GooglePackages/710/com.google.external-dependency-manager-1.2.165.tar",
"com.google.firebase.analytics": "file:../Tarballs/GooglePackages/710/com.google.firebase.analytics-7.1.0.tar",
"com.google.firebase.app": "file:../Tarballs/GooglePackages/710/com.google.firebase.app-7.1.0.tar",
"com.google.firebase.crashlytics": "file:../Tarballs/GooglePackages/710/com.google.firebase.crashlytics-7.1.0.tar",
"com.google.firebase.messaging": "file:../Tarballs/GooglePackages/710/com.google.firebase.messaging-7.1.0.tar",
"com.google.firebase.remote-config": "file:../Tarballs/GooglePackages/710/com.google.firebase.remote-config-7.1.0.tar",
```
#### 3. Google Play
We use:
- InApp Store Rating

Download these packages at https://developers.google.com/unity/archive

```
"com.google.android.appbundle": "file:../Tarballs/GooglePackages/play/com.google.android.appbundle-1.4.1.tgz",
"com.google.play.common": "file:../Tarballs/GooglePackages/play/com.google.play.common-1.4.1.tgz",
"com.google.play.core": "file:../Tarballs/GooglePackages/play/com.google.play.core-1.4.1.tgz",
"com.google.play.review": "file:../Tarballs/GooglePackages/play/com.google.play.review-1.4.1.tgz",
```
#### 4. Appslfyer
- https://github.com/AppsFlyerSDK/appsflyer-unity-plugin

***Problems and Tips:***
1. Unity cannot handle deeplink when using Appsflyer package. 
2. So We need to change a little bit Appsflyer code and build it as a tarball that ca be used as a package.

```
"appsflyer-unity-plugin": "file:../Tarballs/AppsFlyerPackages/appsflyer-unity-plugin-6.3.1.tgz",
```
  
#### 5. Ironsrouce
- https://developers.ironsrc.com/ironsource-mobile/unity/unity-plugin/#step-3
#### 6. iOS 14 ATT
- https://github.com/Unity-Technologies/com.unity.ads.ios-support

```
"com.unity.ads.ios-support": "1.0.0",
```
