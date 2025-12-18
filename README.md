# 微信群聊总结助手
[项目地址](https://github.com/Vita0519/wechat_summary/)
一个基于人工智能的微信群聊消息总结工具，支持多种AI服务，可以自动提取群聊重点内容并生成结构化总结。

## 功能特点

- 🤖 支持多种AI服务（DeepSeek、Kimi、通义千问等）
- 📝 自定义提示词模板
- 💬 自动获取群聊消息
- 📊 生成结构化总结
- 💾 保存总结到本地
- ✉️ 发送总结到群聊
- 🎨 现代化界面设计
- 🔒 API密钥安全存储

## 安装说明

### 环境要求
**仅支持微信4.0以下，wxauto版本3.9.11.17.5**

- Python 3.8+
- Windows 操作系统
- 微信桌面版

### 依赖安装

```bash
pip install -r requirements.txt
```

### 运行程序
```bash
python wechat_summary_gui.py
```

## 使用截图
![使用截图](使用截图.png)
![AI服务](V2/AI服务配置.png)
![提示词配置](V2/提示词配置.png)

## 使用说明

### 1. 配置AI服务

在首次使用前，需要配置AI服务的API密钥：

1. 打开程序，切换到"AI服务配置"标签页
2. 选择要使用的AI服务（DeepSeek/Kimi/通义千问）
3. 填写对应的API密钥
4. 点击保存

### 2. 获取群聊总结

1. 在主界面输入：
   - 群聊名称：要总结的微信群名称
   - 获取小时数：要获取多少小时内的消息
   - AI服务：选择要使用的AI服务
2. 点击"获取群聊消息"按钮
3. 等待AI生成总结

### 3. 处理总结结果

生成总结后，您可以：

- 直接查看总结内容
- 点击"保存总结"将内容保存到本地文件
- 点击"发送到群聊"将总结发送回群聊

### 4. 自定义提示词

如果需要调整总结的风格和内容：

1. 切换到"提示词配置"标签页
2. 编辑提示词模板
3. 点击"保存提示词"使其生效
4. 如需恢复，可点击"恢复默认"

## 目录结构

- `wechat_summary.py`：主程序文件
- `wechat_summary_gui.py`：图形界面文件
- `config.json`：配置文件
- `summary`：总结文件夹

## 免责声明
- 这个项目免费开源，不存在收费。
- 本工具仅供学习和技术研究使用，不得用于任何商业或非法行为。
- 本工具的作者不对本工具的安全性、完整性、可靠性、有效性、正确性或适用性做任何明示或暗示的保证，也不对本工具的使用或滥用造成的任何直接或间接的损失、责任、索赔、要求或诉讼承担任何责任。
- 本工具的作者保留随时修改、更新、删除或终止本工具的权利，无需事先通知或承担任何义务。
- 本工具的使用者应遵守相关法律法规，尊重微信的版权和隐私，不得侵犯微信或其他第三方的合法权益，不得从事任何违法或不道德的行为。
- 本工具的使用者在下载、安装、运行或使用本工具时，即表示已阅读并同意本免责声明。如有异议，请立即停止使用本工具，并删除所有相关文件。
- 代码仅用于对UIAutomation技术的交流学习使用，禁止用于实际生产项目，请勿用于非法用途和商业用途！如因此产生任何法律纠纷，均与作者无关！


## 联系方式

<div align="center"><table><tbody><tr><td align="center"><b>个人QQ</b><br><img src="https://wmimg.com/i/1119/2025/02/67a96bb8d3ef6.jpg" width="250" alt="作者QQ"><br><b>QQ：154578485</b></td><td align="center"><b>QQ交流群</b><br><img src="https://github.com/user-attachments/assets/5f24482c-19fd-4aa5-8861-3a92a5fc5c79" width="250" alt="QQ群二维码"><br><small>群内会更新个人练手的python项目</small></td><td align="center"><b>微信赞赏</b><br><img src="https://wmimg.com/i/1119/2024/09/66dd37a5ab6e8.jpg" width="500" alt="微信赞赏码"><br><small>要到饭咧？啊咧？啊咧？不给也没事~ 请随意打赏</small></td><td align="center"><b>支付宝赞赏</b><br><img src="https://wmimg.com/i/1119/2024/09/66dd3d6febd05.jpg" width="300" alt="支付宝赞赏码"><br><small>如果觉得有帮助,来包辣条犒劳一下吧~</small></td></tr></tbody></table></div>

---

### 📚 推荐阅读

-   [WeChatAI](https://github.com/Vita0519/WeChatAI)
-   [历时两周半开发的一款加载live2模型的浏览器插件](https://www.allfather.top/archives/live2dkan-ban-niang)
-   [PySide6+live2d+小智 开发的 AI 语音助手桌面精灵，支持和小智持续对话、音乐播放、番茄时钟、书签跳转、ocr等功能](https://www.bilibili.com/video/BV1wN9rYFEze/?share_source=copy_web&vd_source=f3d1033524bcd51cf10e8312ef8376ff)
-   [github优秀开源作品集](https://www.allfather.top/mol2d/)

---
