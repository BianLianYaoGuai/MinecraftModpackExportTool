# MinecraftModpackExportTool
将你的Minecraft游戏文件夹导出成CurseForge整合包格式，可发给好友，供PCL2等启动器一键安装
## 运行方法：
- 1.安装PySide2库
- 2.运行mmet.py

备注：目前暂不支持neoforge，需要导出后手动修改manifest.json
```json
// manifest.json修改示例
{
	"minecraft": {
		"version": "1.20.1",
		"modLoaders": [{
			"id": "NeoForge-47.1.106",
			"primary": true
		}]
	},
	"manifestType": "minecraftModpack",
	"manifestVersion": 1,
	"name": "1.20.1-NeoForge_47.1.106",
	"version": "1.0.0",
	"author": "BLYG",
	"files": [],
	"overrides": "overrides"
}
```
