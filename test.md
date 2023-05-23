## 发布子模块改动

> 对所有推送都执行检查，那么可以通过设置 git config push.recurseSubmodules check 让它成为默认行为
- 可以通过设置 git config push.recurseSubmodules check 让它成为默认行为。

- git config submodule.recurse true

- git config --global diff.submodule log


> 如果你设置了配置选项 status.submodulesummary，Git 也会显示你的子模块的更改摘要：
- git config status.submodulesummary 1

>
- git config -f .gitmodules submodule.reading-notes.branch feature-add-submodule  [不用 -f .gitmodules 选项，那么它只会为你做修改。但是在仓库中保留跟踪信息更有意义一些，因为其他人也可以得到同样的效果]

- git submodule update --remote  [更新并检出子模块仓库]
