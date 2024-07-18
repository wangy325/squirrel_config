

这是一份自用squirrel输入方案的配置备份。

### 如何使用

- 下载或者clone项目
- 备份Rime原本的配置
    `cp -r ~/Library/Rime ~/Desktop/rime_bak`
- 复制文件夹中的配置文件内容到Rime配置目录
    ```
    cd Rime
    rm -rf *
    cp -r squirrel_config/1hbx/* .
    ```
- 修改或者删除自动备份配置
    修改`installation.yaml`
    ```yaml
    # 或者删除以下行
    sync_dir: '/your/backup/dir'
    ```
- 重新部署

### 已经配置的功能

- 明月全拼
- 小鹤双拼
- 快速输入emoji
- 符号快速上屏
- 中英文混输
- 自定义词典
- 搜狗拓展词库
- luna脚本（快速输入日期时间等）
- 配置备份
- 自定义皮肤
- ...

### 参考

[Rime中州韻輸入引擎安裝與簡單調試記錄](https://wangy325.github.io/zh/posts/10_Rime%E4%B8%AD%E5%B7%9E%E9%9F%BB%E8%BC%B8%E5%85%A5%E5%BC%95%E6%93%8E%E5%AE%89%E8%A3%9D%E8%88%87%E7%B0%A1%E5%96%AE%E8%AA%BF%E6%95%99/)

