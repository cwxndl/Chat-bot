# Chat-bot

## 环境依赖
```bash
# 如果想快速开始预训练，这里请先安装需要的pip包
pip install -r chat-bot-requirement.txt
```
## 快速开始
首先启动您的后端API：
- 如果您使用Qwen1.5相关的大模型，请在qwen2_api.py中自行修改您需要的模型名称（代码文件第12行）： MODEL_NAME = 'qwen/Qwen1.5-1.8B-Chat' #这里以qwen1.5-1.8B-Chat为例
  ```bash
  # 执行下面的命令
  python qwen2_api.py
  ```
- 后端启动API后即可执行我们的webui:
  ```bash
  python app_qwen.py
  ```
## webui界面示例

<div align="center">
<img src="./assets/chat_bot1.gif" width="750" >
</div>
