# openim-chat

## 🧩 Feature Overview

1. This repository implements a business system, which consists of two parts: User System and Backend Management System.
2. The system relies on the [open-im-server repository](https://github.com/openimsdk/open-im-server) and implements various business functions by calling the APIs of the instant messaging system.
3. The User System includes regular functions such as user login, user registration, user information update, etc.
4. The Backend Management System includes APIs for managing users, groups, and messages.

## :busts_in_silhouette: Community

- 💬 [Follow our Twitter account](https://twitter.com/founder_im63606)
- 🚀 [Join our Slack community](https://join.slack.com/t/openimsdk/shared_invite/zt-2ijy1ys1f-O0aEDCr7ExRZ7mwsHAVg9A)
- :eyes: [Join our WeChat group](https://openim-1253691595.cos.ap-nanjing.myqcloud.com/WechatIMG20.jpeg)

## 🛫 Quick Start

> :warning: **Note**: This project works on Linux/Windows/Mac platforms and both ARM and AMD architectures.

### 📦 Clone

```bash
git clone https://github.com/openimsdk/chat openim-chat
cd openim-chat
```

### 🛠 Initialization

:computer: Before the first compilation, execute on Linux/Mac platforms:

```
sh bootstrap.sh
```

:computer: On Windows execute:

```
bootstrap.bat
```

### 🏗 Build

```bash
mage
```

### 🚀 Start

```bash
mage start
```

### :floppy_disk: Or start in the background and collect logs

```
nohup mage start >> _output/logs/chat.log 2>&1 &
```

### :mag_right: Check

```bash
mage check
```

### 🛑 Stop

```bash
mage stop
```

### 🚀 Start Sequence

1. Successfully start [open-im-server](https://github.com/openimsdk/open-im-server).
2. Compile chat `mage`.
3. Start chat `mage start`.

## 📞 If you want to enable audio and video calls, please configure LiveKit

:link: Please refer to "[How to set up LiveKit server](./HOW_TO_SETUP_LIVEKIT_SERVER.md)".

## :handshake: Contributing

:heart: Contributions to this project are welcome! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## 🚨 License

This software is licensed under the Apache License 2.0



# Auto-deployment Test - 2025-11-03 00:49:51
