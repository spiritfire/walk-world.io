# 🌍 Walk World | 漫步世界
> **Run the world from your living room. / 足不出户，漫步世界。**
> try by below link (on android or apple phone, i test on android chrome, i don't know if apple works well because i don't have iphone)
> https://spiritfire.github.io/walk-world
> [English](#english) | [中文](#chinese)

---

<a name="english"></a>
## 🇬🇧 English

### 📖 Introduction & Motivation
**Walk World** is a lightweight, single-file HTML5 web application designed to turn indoor fitness into an immersive travel experience.

The concept was born from a simple idea: **Why stare at a wall while walking in place?**

By utilizing the accelerometers and gyroscopes found in every modern smartphone, this app allows you to "physically" walk through high-definition videos. When you walk, the video plays at a speed matching your pace. When you stop, the video stops. If you turn your body (or phone), the view pans left or right, simulating a VR experience without a headset.

**Our Vision:** To build a global "Walk World" community. We envision a future where users from all over the planet upload 4K walking tours of their hometowns, scenic spots, or bustling cities—complete with voice narration/guides. A user in New York could take a morning walk through the streets of Tokyo, while a user in London explores the Great Wall of China, getting healthy while seeing the world.

### ✨ Key Features
*   **🏃‍♂️ Physics-Based Engine:** The video playback rate correlates precisely with your step cadence and stride length.
*   **📱 Pseudo-VR Experience:** Uses the device gyroscope. If you turn your phone left/right, the video pans, simulating a wide field of view.
*   **⚡ Instant Response:** Features "Catapult Start" logic. The video moves the instant you take a step—no lag.
*   **🔊 Immersive Feedback:** Haptic vibration and audio feedback on every step (can be toggled).
*   **🔒 Privacy First:** Currently runs entirely client-side. Videos are loaded from your local device; no data is uploaded.
*   **🚀 Zero Dependencies:** Pure Vanilla JavaScript. One single HTML file. No build process required.

### 🛠️ How to Use
1.  **Prepare a Video:** Download a "4K Walking Tour" video (POV style) to your phone (e.g., from YouTube).
2.  **Deploy/Run:**
    *   Host the `index.html` on GitHub Pages, Vercel, or any HTTPS server (Required for sensor access).
    *   Or transfer the file to your phone and open it (Note: Local file access to sensors might be restricted on some browsers).
3.  **Start Walking:**
    *   Open the link on your phone.
    *   Click **"Select Video"** and choose your walking tour file.
    *   Click **"Start"**.
    *   Hold your phone vertically and start walking in place!
    *   *Tip:* Use the "Settings" to adjust sensitivity and stride length for the best experience.

### 🗺️ Future Roadmap & Call for Contributions
This is currently a Minimum Viable Product (MVP). **We need developers, designers, and visionaries to help build the full platform.**

We are looking for contributions in:
1.  **Backend & Cloud:** Build a server to host and stream global walking videos.
2.  **Social Features:** User accounts, leaderboards, and the ability to upload/share "Routes" (Video + GPX + Narration).
3.  **Mobile App:** Wrap this web-tech into a native app (React Native/Flutter) for better sensor access and performance.
4.  **Content:** If you have footage of your city, save it! We will need it soon.

Let's build a platform where we can exercise while exploring the beauty of every corner of the world.

---

<a name="chinese"></a>
## 🇨🇳 中文

### 📖 初衷与愿景
**Walk World (漫步世界)** 是一个轻量级的单文件 HTML5 应用，旨在将枯燥的室内原地踏步健身转化为一种沉浸式的“云旅游”体验。

这个项目的诞生源于一个简单的想法：**与其对着墙壁原地踏步，不如走进风景里。**

通过调用现代智能手机中的加速度计和陀螺仪，本应用让您能够“物理上”地行走在高清视频中。您走得越快，视频播放越快；您停下，视频即止。如果您左右转动身体（或手机），画面也会随之平移，模拟出一种无需头显的 VR 体验。

**我的愿景：** 建立一个全球化的“漫步世界”社区。未来，一定要将其做到服务器上，让全世界的用户都能上传自己家乡城市、风景名胜的 4K 漫步视频，甚至配上声音讲解。让身在纽约的用户可以在早晨“漫步”于东京的街头，让伦敦的用户可以探索中国的长城。既锻炼了身体，又能领略世界各国的风情。

### ✨ 主要功能
*   **🏃‍♂️ 物理步速引擎：** 视频播放速度根据您的步频和步长精密计算，拒绝滑步感。
*   **📱 伪 VR 全景体验：** 利用手机陀螺仪，左右转动手机即可查看画面两侧的风景，仿佛置身其中。
*   **⚡ 零延迟起步：** 内置“弹射起步”逻辑，迈出第一步视频即刻响应，彻底告别起步卡顿。
*   **🔊 沉浸式反馈：** 每走一步都有震动和脚步声反馈（可设置开关），让运动更有节奏感。
*   **🔒 隐私安全：** 目前版本完全在本地运行（Client-side）。视频直接读取手机相册，不上传任何数据。
*   **🚀 极简架构：** 纯原生 JavaScript 编写，只有一个 HTML 文件，无需安装任何依赖。

### 🛠️ 使用方法
1.  **准备视频：** 下载一段第一人称视角（POV）的城市或风景漫步视频到您的手机相册（推荐 4K 画质）。
2.  **运行应用：**
    *   推荐：将代码部署到 GitHub Pages 或任何 HTTPS 服务器上（手机浏览器访问传感器通常需要 HTTPS）。
    *   或者：将 HTML 文件传到手机直接用浏览器打开（部分浏览器可能限制本地文件的传感器权限）。
3.  **开始漫步：**
    *   用手机浏览器访问链接。
    *   点击 **“选择视频”** 并加载您的视频文件。
    *   点击 **“全屏出发”**。
    *   竖持手机，开始原地踏步！
    *   *提示：* 点击设置可以调节灵敏度、步长以及 VR 方向。

### 🗺️ 路线图与共建邀请
目前这是一个最小可行性产品（MVP）。**我们诚挚邀请全球的高手们加入，共同完善这个 App。**

我们需要以下方面的帮助：
1.  **服务器端开发：** 建立视频托管平台，支持全球用户上传、分享和流式播放漫步视频。
2.  **功能完善：** 增加用户系统、排行榜、心率设备连接功能。
3.  **原生应用：** 将其封装为 iOS/Android 原生应用（React Native/Flutter），以获得更好的性能和传感器权限。
4.  **内容生态：** 如果您有家乡的漫步视频，请保留好！未来我们将建立全球漫步地图。

让我们一起打造一个“真正的 Walk World”，让健身不再枯燥，让世界触手可及。

---

## 📄 License
MIT License. Feel free to fork, modify, and distribute. Let's make the world healthier and more connected.
