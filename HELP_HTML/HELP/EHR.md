# EHR 模组安装与更新教程

## 模组安装教程
1. **下载 EHR**  
   下载地址：[https://github.com/Gurge44/EndlessHostRoles/release/latest](https://github.com/Gurge44/EndlessHostRoles/release/latest)  
   - **Steam 版本**：下载 `EHR.版本号_Steam.zip`  
   - **Epic 或微软商店版本**：下载 `EHR.版本号_Epic-Games_Microsoft-Store.zip`  

2. **找到 Among Us 文件夹并安装模组**  
   - **Steam**  
     1. 右键 Among Us → 管理 → 浏览本地文件（示例路径：`C:\Program Files (x86)\Steam\steamapps\common\Among Us\`）  
     2. 将下载的模组压缩包解压到游戏目录  
   - **Epic**  
     1. 找到路径：`C:\Program Files\Epic Games\AmongUs\`  
     2. 将下载的模组压缩包解压到游戏目录  
   - **微软商店**  
     1. 一般路径：`C:\Program Files\WindowsApps\...`（通过系统变量查找）  
     2. 将下载的模组压缩包解压到游戏目录  

   *提示：Steam 版本可复制游戏副本后再安装模组，避免影响原文件。*


## 模组更新教程
1. **下载新的 EHR.dll**  
   下载地址：[https://github.com/Gurge44/EndlessHostRoles/release/latest](https://github.com/Gurge44/EndlessHostRoles/release/latest)  

2. **替换旧版本 EHR.dll**  
   1. 按照安装教程中的方法找到游戏文件夹  
   2. 进入目录：`/BepInEx/plugins`  
   3. 用新下载的 `EHR.dll` 替换旧文件