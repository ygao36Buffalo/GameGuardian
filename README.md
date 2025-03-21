# GameGuardian

GameGuardian 是一款能够 **实时捕捉用户情绪变化** 的应用程序，专为提升游戏体验而设计。它可在后台运行，通过 **视频捕捉您的表情**，推测您的情绪状态，并结合 **当前游戏场景**，提供 **智能、个性化的交互**。我们的目标是帮助玩家 **减少游戏中的负面情绪**，优化整体游戏体验，并避免长时间游戏可能带来的身体与心理负担。

## 📥 安装与使用指南

**⚠️ 请在下载和使用 GameGuardian 之前先阅读以下说明！**

### 📌 当前版本信息
- **支持平台**：目前仅支持 **Android 设备**
- **安装文件**：[`GameGuardian.apk`](https://github.com/ygao36Buffalo/GameGuardian/releases/tag/GameGuardian.1.3.4#)

### 📌 安装步骤
1. **下载** 请点击`GameGuardian.apk` 下载并安装。
2. **授予必要权限**
   - **相机权限**：用于捕捉您的表情，以评估情绪状态（所有摄像数据输入本地模型后会得出情感评估数值，**不会上传云端，也不会存储于本地**。）。
   - **录屏权限**：用于记录游戏画面，仅在情绪波动时触发保存 **近 5 秒游戏截图**，并上传至服务器以便进一步分析。
   - **弹窗权限**：用于在关键时刻提供个性化情绪干预提醒。
3. **系统设置**
   - **电池管理**：设置中，电池->后台耗电管理->GameGuardian允许后台高耗电。
   - **多任务窗口**：多任务窗中选择GameGuardian，锁定。（可选
   - **游戏设置**：如果感到游戏卡顿，可以降低游戏的画质和帧率。
4. **注意事项**
   - **录屏**：在情绪波动时会触发连续5秒的游戏截屏（存在一定几率的误触发），因此为了保护您的隐私，请尽量**不要在游戏过程中切换界面**（例如微信等）。


## 🎮 主要功能
- **实时情绪检测**：基于面部表情分析，智能识别愤怒、焦虑、兴奋等情绪。
- **游戏环境感知**：结合游戏画面，判断当前游戏情境，提供适当的反馈。
- **个性化干预**：当情绪波动剧烈时，App 会提供个性化的交互，帮助调整心态。
- **录屏分析**：当检测到强烈情绪变化时，自动截取 **5 秒游戏内容** 并上传，以优化情绪分析算法。

## 🧭使用指南
1. 打开app进入首页，可选择不同游戏类型，并选择基础回复/大模型回复。完成设置后，点击“确认设置”。当选择“其他游戏”，会默认先进入竖屏模式。如果游戏的视图方向和当前页面不同，请点击“rorate view”来选转屏幕方向，以达到和游戏方向一致。

2. 进入控制页面，第一次会请求相机权限、存储权限、屏幕捕捉权限，同意即可。在玩家游戏开始前，点击“开始追踪”，选择同意录制的屏幕，然后同意其请求通知权限。

3. 开始追踪用户情绪后，用户切换到游戏画面，进入对局。如果检测到玩家出现情绪波动，该软件会返回安慰、鼓励到话语，以达到干预玩家负面情绪、缓解玩家烦躁、愤怒的目的。请注意，服务启动过程中，请不要打开含个人敏感信息的页面。也请不要再次点击“旋转视图”，以防识别不准确，

4. 当完成一局游戏后，或是想结束录制状态时，用户可切换回GameGuardian软件，“停止追踪”。结束实时干预的服务。

5. 玩家可多次使用GameGuardian的服务。当玩家使用情绪干预服务一段时间后，可向我们反馈体验。我们将继续努力。

## 📝 体验反馈
为了改进 GameGuardian，我们希望收集您的使用反馈！

➡️ **请在体验完 App 后填写我们的问卷调查**：[调查问卷](https://www.wjx.cn/vm/msUKbj1.aspx#)

您的反馈将帮助我们优化情绪识别算法，并提供更好的游戏体验！

## 🔒 隐私与数据安全
- **本地存储**：少量情绪识别数据和游戏截屏数据。
- **上传云端**：录屏功能仅在情绪波动时 **触发 5 秒录制**，用于分析游戏情境，并 **上传至服务器** 以改善干预策略。
- **用户数据保护**：任何人无法得到您存在本地的任何数据，除非您保存后分享给别人。如需实验，在进行数据采集之前，我们一定会让用户知情，并取得同意。我们承诺不会滥用或泄露您的数据，所有数据仅用于情绪分析。

## 📬 联系我们
如果您有任何问题或建议，请通过以下方式联系我们：
- **Contact**: 郑睿豪
- **Email**: ruihaozheng@qq.com

**感谢您的参与与支持！🎮💙**
