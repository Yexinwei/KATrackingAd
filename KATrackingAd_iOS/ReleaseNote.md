# 版本发布记录

## Ver3.5.4
## Release Date: 2018-9-29

* 修复bug,优化SDK
* 聚合AppsFlyer，更新头条SDK，删掉CTSDK

## Ver3.5.3
## Release Date: 2018-8-23

* 修复bug,优化SDK

## Ver3.5.2
## Release Date: 2018-8-17

* 聚合新增平台 Facebook
* 修复bug

## Ver3.5.1
## Release Date: 2018-8-1

* 修复Bug

## Ver3.5
## Release Date: 2018-8-1

* 聚合新增平台 AppLovin, IronSource, Toutiao
* 广告展示形式优化
* 修复Bug

## Ver3.4.4
## Release Date: 2018-7-3

* 调整落地页展示形式，延迟显示

## Ver3.4.3
## Release Date: 2018-7-2

* 修复原生广告角标显示不正确问题

## Ver3.4.2
## Release Date: 2018-6-28

* 获取用户Country_code不正确修复

## Ver3.4.1
## Release Date: 2018-6-26

* 修复对VungleSDK的一个字段依赖

## Ver3.4
## Release Date: 2018-6-20

* 添加debugMode，便于对接过程中测试
* 优化原生广告PrimaryView展示形式，广告角标尺寸大小调整
* 开屏广告添加底部产品标识填充功能
* 添加横幅广告形式
* Resources.bundle 增加横幅广告相关素材，需要更新

## Ver3.3.3
## Release Date: 2018-6-6

* 修复一个聚合的Bug

## Ver3.3.2
## Release Date: 2018-6-5

* KAAdNative增加返回广告类为参数的失败回调
* KAAdNative增加渲染模式控制
* 修复落地页渲染Bug

## Ver3.3.1
## Release Date: 2018-5-15

* 修复原生广告点击事件重复上报bug

## Ver3.3
## Release Date: 2018-5-11

* 相较于3.3之前的版本，KAAdNative添加了以下修改以及结构变化
* KAAdNative 增加聚合功能
* isReady方法删除，仅供根据广告请求成功回调判断广告获取成功
* ka_adIconImageView 修改成 ka_adIcon, UIImage
* ka_adImage 大图广告素材通过 primaryViewOfSize 方法获取
* 增加 recyclePrimaryView 方法回收广告资源
* nativeAdLandingPageAtPoint 现在返回 NSURL
