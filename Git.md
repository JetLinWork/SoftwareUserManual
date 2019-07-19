## Git

## 安装
>Git官方网站: https://git-scm.com/

>Git完整命令手册地址: http://git-scm.com/docs 


## 查看版本
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


##