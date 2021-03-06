---
title: 内存
header: develop
nav: api
sidebar: device_onmemory
---

## swan.onMemoryWarning

**解释：**监听内存不足的告警事件，Android 下有告警等级划分，只有 LOW 和 CRITICAL 会回调开发者；iOS 无等级划分。

**方法参数：**Function callback

**`callback`参数说明：**

|参数名 |类型  |必填 | 默认值 |说明|
|---- | ---- | ---- | ----|----|
|level |Number |是|-|仅 Android 有该字段，对应系统内存告警等级宏定义。|

Android下告警等级对应系统宏：

```
TRIM_MEMORY_RUNNING_MODERATE = 5
TRIM_MEMORY_RUNNING_LOW = 10
TRIM_MEMORY_RUNNING_CRITICAL = 15
```
**示例：**

```js
swan.onMemoryWarning(function (res) {
    console.log('onMemoryWarningReceive')
});
```
<!-- #### 错误码

**Andriod**

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确。|
|1001|执行失败|

**iOS**

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确。| -->