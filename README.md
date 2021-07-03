# realbizgames-unity-common-init-chain

![The product concept](Images~/Lego_Concept.jpeg)

# The Concept
1. Games contain many of the same reusable components.
2. Build these "the same reusable components" into many simple, stable, scalable smaller projects.
3. Combine them to make a big game project.


Let's start from NOW or NEVER.
  
# Inhouse Components

#### 1. Rule Pattern Template.

We use:
- Build common rule patterns that can be used in many projects.
- https://github.com/truonguit2010/realbizgames-rule-pattern.git

```
"com.realbizgames.pattern.rule": "https://github.com/truonguit2010/realbizgames-rule-pattern.git#v1.0.0",
```
#### 2. Chain Pattern Template

We use:
- Build common chain patterns that can be used in many projects.
- https://github.com/truonguit2010/realbizgames-unity-chain-pattern.git

```
"com.realbizgames.pattern.chain": "https://github.com/truonguit2010/realbizgames-unity-chain-pattern.git#v1.0.0",
```
#### 3. RealbizGames Data Utility Package
We use:
- Store data in PlayerPref (Device Local Storage).
- Get Data From Firebase Remote Config.
- Get Data From Our BackEnd Service.
- https://github.com/truonguit2010/realbizgames-data.git

```
"com.realbizgames.data": "https://github.com/truonguit2010/realbizgames-data.git#v1.0.0",
```

#### 4. RealbizGames Deep Link Package
We use:
- Rule Pattern to handle the DeepLink.
- Auto show Store Rating In-app Dialog via Deeplink.
- https://github.com/truonguit2010/realbizgames-unity-deeplink.git

```
"com.realbizgames.deeplink": "https://github.com/truonguit2010/realbizgames-unity-deeplink.git#v1.0.0",
```

#### 5. RealbizGames Game Config Package.
We use:
- Config Ad ids.
- Config Enable Debug Log.
- And more ....
- https://github.com/truonguit2010/realbizgames-game-config.git

```
"com.realbizgames.game.config": "https://github.com/truonguit2010/realbizgames-game-config.git#v1.0.0",
```

#### 6. RealbizGames IAP MasterData.
We use:
- Define IAP product items.
- https://github.com/truonguit2010/realbizgames-masterdata-iap.git

```
"com.realbizgames.masterdata.iap": "https://github.com/truonguit2010/realbizgames-masterdata-iap.git#v1.0.0",
```

#### 7. RealbizGames Banner Ad Settings.
We use:
- Config where to show banner ad.
- Config how to show banner ad.
- https://github.com/truonguit2010/realbizgames-banner-ads-setting.git

```
"com.realbizgames.settings.banner": "https://github.com/truonguit2010/realbizgames-banner-ads-setting.git#v1.0.0",
```
#### 8. RealbizGames Interstitial Ad Settings.
We use:
- Config where to show interstitial ad.
- Config how to show interstitial ad.
- https://github.com/truonguit2010/realbizgames-interstitial-ads-setting.git

```
"com.realbizgames.settings.interstitial": "https://github.com/truonguit2010/realbizgames-interstitial-ads-setting.git#v1.0.0",
```

    "com.realbizgames.settings.dialog.iap": "https://github.com/truonguit2010/realbizgames-iap-dialog-config.git#v1.0.0",
    
    "com.realbizgames.shopping": "https://github.com/truonguit2010/realbizgames-unity-shopping.git#v1.0.0",
    "com.realbizgames.storerating": "https://github.com/truonguit2010/realbizgames-unity-storerating.git#v1.0.0",
    "com.realbizgames.userplayingdata.gamesetting": "https://github.com/truonguit2010/realbizgames-userplayingdata-gamesetting.git#v1.0.0",
    "com.realbizgames.userplayingdata.highscore": "https://github.com/truonguit2010/realbizgames-userplayingdata-highscore.git#v1.0.0",
    "com.realbizgames.userplayingdata.userads": "https://github.com/truonguit2010/realbizgames-userplayingdata-ads.git#v1.0.0",
    "com.realbizgames.userplayingdata.userlevel": "https://github.com/truonguit2010/realbizgames-upd-userlevel.git#v1.0.0",

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
#### 7. Unity Purchasing
- https://docs.unity3d.com/Manual/com.unity.purchasing.html
```
"com.unity.purchasing": "3.2.1",
```

