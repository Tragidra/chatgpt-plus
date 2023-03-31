# Wechat-GPT

基于 ChatGPT 的聊天应用

## TODOLIST

* [x] 使用 level DB 保存用户聊天记录
* [x] 用户聊天鉴权，设置口令模式
* [x] 定期清理不在线的会话 sessionID 和聊天上下文记录
* [x] 给 Token 设置调用次数
* [x] OpenAI API 负载均衡，限制每个 API Key 每分钟之内调用次数不超过 15次，防止被封
* [x] 角色设定，预设一些角色，比如程序员，客服，作家，老师，艺术家...
* [x] markdown 语法解析和代码高亮
* [ ] 用户配置界面，配置用户的使用习惯，可以让用户配置自己的 API KEY，调用自己的 API Key，将不记 Token 的使用次数
* [ ] 嵌入 AI 绘画功能，支持根据描述词生成图片
* [x] 点卡用完之后，提示加入知识星球
* [ ] 增加 Buffer 层，将相同的问题答案缓存起来，相同问题直接返回答案。
* [ ] 界面改版，支持创建会话功能，支持发语音
* [x] 允许修改角色训练数据 

