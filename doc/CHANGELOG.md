# 更新日志

- v1.2.0
    - 修复高危漏洞，必须更新
    
- v1.1.0
    - 由单文件改为多文件，方便维护，提供dist目录，方便复制粘贴。
    - 删除和新增部分配置，提供兼容性代码，方便升级。
    - 修改KV key生成逻辑，可能导致之前的数据丢失，可手动修改key或重新配置。
    - 修复部分bug
    - 自动绑定所有指令
    - BREAKING CHANGE： 重大改动，必须把群ID加到白名单`CHAT_GROUP_WHITE_LIST`才能使用, 否则任何人都可以把你的机器人加到群组中，然后消耗你的配额。

- v1.0.0
    - 初始版本