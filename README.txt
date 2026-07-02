===========================================
  交互美学幻灯片 - 使用说明
===========================================

📦 文件说明
-----------
本项目包含两个版本：

1. index.html (需要服务器)
   - 通过 iframe 加载独立的 pages/*.html 文件
   - 需要通过 HTTP 服务器访问
   - 适合开发和调试

2. index-standalone.html (独立版本) ⭐推荐
   - 所有页面内容已嵌入到主文件中
   - 双击即可直接在浏览器中打开
   - 适合打包交付给客户


🚀 使用方法
-----------

【方法一：双击打开（推荐）】
直接双击 index-standalone.html 文件即可在浏览器中打开。

【方法二：使用启动脚本】
- Windows: 双击 启动.bat
- 也可以双击 本地访问.bat（使用 Chrome 特殊模式）


📱 支持的设备
-------------
✓ Windows / macOS / Linux 桌面浏览器
✓ iPad 横屏 / 竖屏
✓ iPhone / Android 手机横屏 / 竖屏
✓ Chrome / Firefox / Safari / Edge


🎮 操作说明
-----------
- 鼠标拖拽：上下拖动旋转轮盘
- 滚轮：滚动切换卡片
- 键盘：↑ ↓ 方向键切换
- 触摸：在触摸屏上滑动
- 按钮：点击屏幕右侧的上下箭头


🔧 重新生成独立版本
-------------------
如果修改了 pages/ 下的文件，需要重新生成独立版本：

1. 在 PowerShell 中运行：
   .\build-standalone.ps1

2. 或者在命令行中运行：
   powershell -ExecutionPolicy Bypass -File build-standalone.ps1


📊 文件大小
-----------
- index.html: ~15 KB
- index-standalone.html: ~155 KB
- 整个项目（含 pages/）: ~500 KB


💡 提示
-------
- index-standalone.html 文件较大是因为包含了所有 15 个交互页面
- 压缩打包交付时只需要包含 index-standalone.html 即可
- 不需要 pages/ 目录和其他文件


📞 技术支持
-----------
如有问题，请联系开发团队。


===========================================
Reasonix Studio © 2026
===========================================
