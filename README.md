# OFFICE365 E5调用api使E5开发者续订 修复版AutoApi （不使用服务器）

## 说明 ##
* E5自动续期程序，但是**不保证续期**
* 设置了**周六日(UTC时间)不启动**自动调用，周1-5每6小时自动启动一次 （修改看教程）
* 调用api保活：
     * 查询系api：onedrive,outkook,notebook,site等
     * 创建系api: 自动发送邮件，上传文件，修改excel等
 
 * 教程地址: https://www.vvhan.com/officeE5-AutoApi.html
 * 冲冲冲！！！

 * MS_TOKEN为refresh_token，使用rclone获取
 * GH_TOKEN为GitHub key
 * 登陆portal.zaure.com，管理 Microsoft Entra ID -> 应用注册
 * rclone authorize "onedrive" "client_id" "client_secret"
