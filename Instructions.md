# 微·职知识库使用手册

## 更新方法

> 针对 Windows 平台

1. 从 https://git-scm.com/ 下载 Git 并安装

![1537076440236](assets/1537076440236.png)

2. 打开 `git-bash.exe` 接下来的命令操作都是通过其完成

![1537076607636](assets/1537076607636.png)

3. 输入 `ssh-keygen` 生成 ssh 公钥，遇到提示按 `Enter` 使用默认设置即可
4. 输入 `cat ~/.ssh/id_rsa.pub` 查看公钥内容，红框位置为需要复制到 GitHub 的内容

![1537076897888](assets/1537076897888.png)

5. 打开 https://github.com/buptweizhi/knowledge ，进行登录，登录账号及密码在微·职有道云笔记 `第二届参谋部/账号管理.md` 中
6. 在 Settings - Deploy keys 页面点击 `Add deploy key` 新增部署密钥

![1537077349472](assets/1537077349472.png)

7. 将第 4 步复制的 ssh 公钥粘贴到 `Key` 中，`Title` 可以为任意内容（最好能注明是谁添加的），一定要勾选 `Allow write access` 否则无法更新内容，完成后就具备了更新内容的权限

![1537077728556](assets/1537077728556.png)

8. 输入`git clone git@github.com:buptweizhi/knowledge.git` 即可将 GitHub 远程仓库内的知识库内容克隆到本地，在本地编辑 [MarkDown](#MarkDown 介绍) 文本

![1537078375933](assets/1537078375933.png)

9. 内容更新后，依次执行 `git add -A` `git commit -am "更新内容说明"` `git push` 这三条指令即可完成更新



## MarkDown 介绍

> 详细介绍：https://www.appinn.com/markdown/

