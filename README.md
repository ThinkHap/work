gitguide
========

git guide

- 配置
- 使用
    - 版本回退
        HEAD指向的版本就是当前版本，因此，Git允许我们返回版本的历史 使用命令git reset --hard commit_id。
        回退前，用git log可以查看提交历史，以便确定要回退到哪个版本。
        要返回，用git reflog查看命令历史，以便确定要回到后面的哪个版本。
