# AndroidJSInterface接口文档

### 1、显示Toast的消息
##### URL
window.NativeView.showMessage(String message)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|message |ture |string|显示的toast消息 |

### 2、复制文本到剪贴板
##### URL
window.NativeView.copyShareDocument(String text)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|text |ture |string|需要复制的文本 |

### 3、保存图片
##### URL
window.NativeView.savePicture(String[] picUrls)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|picUrls |ture |string数组|保存图片的url |

### 4、微信好友分享网页地址
##### URL
window.NativeView.weChatShare(String webUrl)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|webUrl |ture |string|需要分享的网页url |

### 5、微信朋友圈分享网页地址
##### URL
window.NativeView.weChatFriendShare(String webUrl)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|webUrl |ture |string|需要分享的网页url |

### 6、微信登录
##### URL
window.NativeView.loginByWechat()

### 7、webview页面加载成功回调
##### URL
window.NativeView.onPageLoading(boolean isSuccess)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|isSuccess |ture |boolean|是否加载成功 |

### 8、webview获取Apk的版本号
##### URL
window.NativeView.appVersion()
#### 回调接口
```
javascript:appVersionCallback(versionCode)
```

### 9、清除webview的缓存(有提示信息)
##### URL
window.NativeView.clearCache()
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|isSuccess |ture |boolean|是否加载成功 |

### 10、清除webview的缓存
##### URL
window.NativeView.clearCache(boolean isHideToast)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|isHideToast |ture |boolean|是否隐藏提示信息 |

### 11、校验是否有新版本的APP
##### URL
window.NativeView.checkAppUpdate()

### 12、判断是否是网页的首页
##### URL
window.NativeView.setIsHomeTab(boolean isHomeTab)
#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|isHomeTab |ture |boolean|设置该参数可控制判断是否可以android手机返回键返回网页 |

### 13、获取手机的通用信息
##### URL
window.NativeView.getSystemInfo()
##### 回调
```
"javascript:systemInfoResult('" + PhoneInfoBean.getPhoneInfoString() + "')"
```

### 14、隐藏手机软键盘
##### URL
window.NativeView.hideKeyboard()

### 15、显示手机软键盘
##### URL
window.NativeView.showKeyboard()















