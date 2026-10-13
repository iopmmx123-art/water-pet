【怎么得到APK（不需要安装任何开发环境）】
1. 注册/登录 github.com，点右上角 + → New repository，起名 water-pet，创建。
2. 把本文件夹里的所有内容（包括隐藏文件夹 .github）上传到这个仓库
   （Add file → Upload files。Mac 用 Cmd+Shift+. 显示隐藏文件夹）。
3. 打开仓库的 Actions 页，等待 "Build APK" 跑完（约3-5分钟，变绿勾）。
4. 点进这次运行，页面底部 Artifacts 下载 water-pet-apk，解压得到 app-debug.apk。
5. 传到安卓手机安装（需允许"安装未知来源应用"）。首次打开会请求通知权限，请允许。
