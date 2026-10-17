# Battle Panel UI Android Project

这是可交互 HTML UI 的 Android WebView 包装项目。开关、滑块、导航和主题颜色有界面效果；不连接游戏、不读取或修改游戏进程，也不实现作弊功能。

## 手机端构建 APK（GitHub Actions）
1. 将本 ZIP 解压后，把里面的所有文件上传到 GitHub 仓库根目录（包括 `.github/workflows/build.yml`）。
2. 打开仓库的 **Actions** 标签页。
3. 选择 **Build Android APK**，点击 **Run workflow**（如果 push 已自动触发，也可以直接打开最新运行记录）。
4. 等待任务显示绿色成功，再进入该次运行记录的 **Artifacts** 区域，下载 `Battle-Panel-UI-debug-apk`。
5. 解压下载的 artifact，找到 `app-debug.apk`，在 Android 手机上安装。若手机提示禁止安装未知来源应用，需要只对你使用的文件管理器/浏览器临时允许安装权限。

## Android Studio
也可以在电脑上的 Android Studio 打开此项目并构建 Debug APK。

注意：本环境未安装 Android SDK/Gradle 构建工具，因此这里提供的是完整项目和云端构建流程，并未在此直接生成或验证 APK 文件。
