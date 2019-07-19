## Git

## 安装
>Git官方网站: https://git-scm.com/

>Git完整命令手册地址: http://git-scm.com/docs 


## 查看
>git version

## config设置
+ 设置用户名
    >git config --global user.name "username"
+ 设置邮箱
    >git config --global user.email username@example.com
+ 设置代理提速(解决clone速度较慢的问题)
    + 设置代理(端口号需要自己设置)
        >git config --global https.proxy http://127.0.0.1:1080

        >git config --global https.proxy https://127.0.0.1:1080
    + 取消代理
        >   git config --global --unset http.proxy

        >git config --global --unset https.proxy

## 建立仓库
+ 建立本地仓库（直接使用命令创建或者进入文件夹后使用git init）
    >git init [project-name]
+ 克隆项目
    >git clone [url]


## 修改管理



## 修改同步


## branch分支管理
+ 查看分支
    >git branch
+ 创建分支
    >git branch [branch-name]
+ 切换到对应分支
    >git checkout [branch-name]
+ 删除分支
    >git branch -d [branch-name]
+ 合并分支修改(将branch-name中的修改合并到当前分支)
    >git merge [branch-name]

## tag标签管理
+ 查看标签
    >git tag
+ 创建标签(默认创建当前branch的最近commit)
    >git tag [tag-name]
+ 创建历史commit的标签(给指定的commit打标签)
    >git tag [tag-name] [commit-number]
+ 删除标签
    >git tag -d [tag-name]

## patch管理


