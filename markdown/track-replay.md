# 轨迹回放

## 包名：@incar/track-replay
轨迹回放。

 

## 轨迹回放 ` trackReplayAPI.js`
* ` TrackReplayAPI.prototype.getOrgLicense`  获取组织下所有的车牌号
* `TrackReplayAPI.prototype.getTracks` 获取组织下面一辆车某段时间内的轨迹记录
* `TrackReplayAPI.getOrgLicense`  获取组织下面的车牌号
 
## 行车里程油耗 `travel.js`  
 * ` travel.prototype.dailyMileageFuel`  每日行车里程&平均油耗
 
## 保养记录 ` CareApi.js`
* ` CareApi.getUserRouter`  客户端保养API
* ` CareApi.getStaffRouter` 员工端保养API
* ` CareApi.resolveVehicle` 选择保养车辆
  

## 公开的 ` PubApi.js`

* ` PubApi.sendVerifyCodeSms` 发送验证码
* ` PubApi.checkPhoneNameEmail` 检查手机号码用户名邮件格式
* ` PubApi.register` 用户注册
* ` PubApi.login` 用户登陆
* ` PubApi.resetPwd` 重置密码

## 员工 ` StaffApi.js`
* ` StaffApi.login` 员工登陆
 

## 行车统计 ` StatApi.js`
* ` StatApi.report` 用车报告, 指定时段内用车次数count, 行驶里程mileage, 平均油耗avgOil, 平均车速speed
* ` StatApi.drivingHabit` 驾驶习惯统计,每日急加,急减,急转弯次数
* ` StatApi.oilUsage` 油耗统计, 每日行驶里程Km, 油耗L, 平均油耗L/100Km, 及时间段内总里程,总油耗,平均油耗
* ` StatApi.speedDistribution` 速度段统计
 
## 跟踪 ` TrackApi.js`
* ` TrackApi.recordTrack` 轨迹跟踪记录
* ` TrackApi.getTrack` 查询轨迹

## 里程 ` TripApi.js`
 
* ` TripApi.resolveTrip` 查询轨迹
* ` TripApi.getTrips` 获取里程
* ` TripApi.getTrip` 获取里程
* ` TripApi.getPath` 获取里程路径
* ` TripApi.addTrip` 添加里程
* ` TripApi.addLocation` 增加位置
  
   
## 车辆 ` VehicleApi.js`
* ` VehicleApi.getDetail` 获取车辆信息
 
## 版本 ` VersionApi.js`
  
* ` VersionApi.addApp` 添加APP
* ` VersionApi.getApps` 获取APP
* ` VersionApi.getApp` 获取APP
* ` VersionApi.addVersion` 添加版本号
* ` VersionApi.uploadFile` 上传
* ` VersionApi.getLatestVersion` 获取最后一个版本号
* ` VersionApi.getVersions` 获取所有版本号
* ` VersionApi.deleteVersion` 删除版本号
* ` VersionApi.download` 下载
* ` VersionApi.mkdirsSync` 创建同步
