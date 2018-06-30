# 故障排除

如果您在使用 FoxOne 时遇到问题，请尝试下列建议。

## 打开后黑屏或白屏

如果你使用 Windows 版本：

1. 关闭 FoxOne
2. 设置 Windows 显示隐藏文件，进入 C 盘，找到 Users 文件夹
3. 进入你的用户名命名的文件夹
4. 进入 AppData 文件夹，再进入 Roaming 文件夹。此时的路径应该是 `C:\Users\[你的用户名]\AppData\Roaming`
5. 找到删除 foxone-desktop 文件夹
6. 重启 FoxOne，重新登录。

如果你使用 macOS 版本：

1. 打开访达（Finder），选择菜单“前往 - 前往目录”，或者按下快捷键 `Command Shift G`
2. 输入 `~/Library/Application Support/`，点击“前往”
3. 找到并删除 foxone-desktop 文件夹
4. 重启 FoxOne，重新登录。

## 无法加载行情

- 检查别的需要联网的功能是否正常，例如查看新闻。
- 检查您的互联网连接，检查网络、代理和虚拟专线网络配置
- 尝试别的需要联网的应用程序是否正常工作，例如浏览器。
- 网络连接，并且您的网络设备（例如路由器）已打开。

## 无法交易

### 在“交易所”面板中打开交易所网页进行交易

- 检查网页是否能打开
- 网页中是否提示错误，如果有，请按照错误提示进行操作尝试

### 在“自选/行情”面板中打开交易对进行交易

- 检查自己的 API Key/Secret 是否具备交易权限
- 检查自己的 API Key/Secret 是否已过期

## 无法阅读新闻

- 检查别的需要联网的功能是否正常，例如查看行情
- 参考“无法加载行情”一节的建议

## 无法查阅数据

- 检查别的需要联网的功能是否正常，例如查看行情
- 参考“无法加载行情”一节的建议

## PIN 不正确

- 请多回忆可能使用的 PIN
- 如果无法解决，请[联系 FoxOne 的工作人员](/contacts/README.md)

## 向 FoxOne 提交问题报告

若以上建议都无法解决你的问题，可在 https://github.com/fox-one/Issues/issues 提交问题报告。

**提交须知**

1. 同时留下自己的 Fox.One 邀请码。可以在“左上角头像 - 邀请朋友”查看。
2. 提交的问题报告需包含尽可能多的信息，以便工作人员快速定位和解决：
  1. bug问题截图
  1. 版本号、平台（可引导打开“关于界面”，上面有版本号）
  1. 记录重现过程和步骤
  1. Bug 出现的时间
3. 对于提交问题报告的用户，FoxOne 工作人员一旦核实，未来给予一定的奖励。奖励方式会在奖励形成之日起对用户公布。
4. 如果无法自行报bug，可在 Fox.One 社区向工作人员提交问题信息，并提供自己的 FoxOne 邀请码，等待管理员处理。
