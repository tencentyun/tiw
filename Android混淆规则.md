## 设置混淆规则  

1. 在 proguard-rules.pro 文件，将 TEduBoard SDK 相关类加入不混淆名单：   

```
-keep class com.tencent.teduboard.*  {
    *;
}

-keep class com.tencent.imsdk.** { *; }

-keep class leo.android.cglib.** { *; }

-keep class com.tencent.smtt.** {
	*;
}  

```


