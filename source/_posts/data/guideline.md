---
title: 指标
header: data
nav: book
sidebar: guideline
---


百度小程序相关指标共计 6 大类，37 个指标。

## 用户类指标

|指标名称|详情|
|--|--|
|	新用户数|	90 天内首次启动小程序的用户数。|
|新用户占比	|某时间段内新用户数占启动用户总数的比例。|
|	新用户分布|	某维度的新用户数占全维度的新用户总数的比例。|
|	启动用户数|	启动过小程序的用户数（多次启动不重复计）。|
|	启动用户分布|	某维度的启动用户数占全维度的启动用户总数的比例。|
|	启动次数|	启动小程序的总次数。“一次启动”是指用户打开小程序到主动退出（或超时退出）为止。|
|	启动次数分布|	某维度的启动次数占全维度的启动总次数的比例。|
|	次均使用时长|	平均每一次启动小程序的时间，等于总时长/总启动次数。|
|	人均使用时长|	平均每个用户使用应用程序的时间，等于总时长/总启动用户数。|
|	老用户数|	当日启动用户中，以前也启动过小程序的用户。|
|老用户占比	|当日老用户占总的启动用户的比例。|
|人均启动 次数|	每个用户启动小程序的平均次数。|


## 活跃类指标

|指标名称|详情|
|--|--|
|日活跃用户数|	当日启动过小程序的用户数（多次启动不重复计）。|
|周活跃用户数|	最近 7 天（含查询当日）启动过小程序的用户数（多次启动不重复计）。|
|月活跃用户数|	最近 30 天（含查询当日）启动过小程序的用户数（多次启动不重复计）。|
|日活/周活	|日启动用户数/周启动用户数，反映当日用户活跃与近 7 日的比较水平。|
|日活/月活|	日启动用户数/月启动用户数，反映当日用户活跃与近 30 日的比较水平。|
|流失用户|	最近 60 天（含查询当日）没有启动过小程序的用户数（已去重）。|
|流失率	|流失用户/累计启动用户|

## 留存类指标

|指标名称|详情|
|--|--|
|留存用户数|	某日（周、月）新用户（或启动用户）在目标时间段再次启动小程序的用户数。|
|留存率|	包括：日留存率、周留存率、月留存率。某日（周、月）新用户（或启动用户）在目标时间段再次启动小程序的用户数占原新用户数（或启动用户数）的比例。|


## 页面类指标

|指标名称|详情|
|--|--|
|	访问次数|	页面被访问的次数，多次跳转重复访问也会被计入。|
|	访问用户数|	访问该页面的用户数（同一用户多次访问同一页面不重复计）。|
|	次均停留时长|	平均每一次访问页面的时间，等于页面访问总时长/页面访问总次数。|
|	入口页次数|	该页面作为启动小程序时第一个访问的页面的启动次数。|
|	退出页次数|	该页面作为关闭小程序时最后一个访问的页面的启动次数。|
|	退出率|	该页面作为关闭小程序时最后一个访问页面的启动次数占该页面访问总次数的比例。|
|	访问次数占比|	当前页面访问次数占全部页面访问次数的比例。|
|	停留时长占比|	用户访问当前页面的停留时长的总和占用户在全部页面的停留时长总和的比例。|

## 使用习惯类指标

|指标名称|详情|
|--|--|
|	访问深度分布|	访问深度指一次启动过程的去重访问页面数；分布指不同访问深度的启动次数分布。|
|使用时长分布|	不同访问时长的启动次数分布|
|	使用频率分布|	启动频率指用户的日启动次数，如用户在 1 月 1 日启动了 2 次；在 1 月 2 日启动了 4 次，则该用户在日启动次数 2 次和 4 次两个分布上均会被计入 1 次。|
|	使用间隔分布|	启动间隔指用户最近一次启动距离上一次启动的时长；分布指不同启动间隔的启动用户数分布，其中新用户仅有 1 次启动，启动间隔为“首次启动”；用户最近一次启动与上一次启动在同一天的间隔为“当日”。|

## 数据分析维度

|维度|内容|
|--|--|
|终端系统平台|安卓、苹果、其它|
|系统版本|iOS 及 Android 逐个子版本|
|设备品牌|如苹果、三星、华为、小米等|
|设备型号|如 iPhone8、小米 5、华为荣耀等|
|联网方式|如 wifi、3g/4g、2g 等|
|分辨率|如 640*960 等|
|运营商|中国移动、联通等|
|百度APP的版本号| 10.7 等|
|页面|每一条页面路径，即为一个页面。|


