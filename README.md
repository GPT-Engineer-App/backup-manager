# backup-manager

1.数据库异地备份工具开发
你好，帮我开发一个数据库管理系统，实现对多台服务器的数据库管理工作：
一、前端（vue.js）
1.主页：显示所有的服务器和数据库信息；
2.服务器管理页面：可以添加、删除和修改服务器信息；
3.数据库管理页面：可以添加、删除和修改数据库信息；
4.备份管理页面：可以查看所有的备份任务，包括定时备份和手动备份。可以添加删除和修改备份任务。可以手动触发备份任务。
二、后端(python+flask)
提供各种API给前端调用，包括获取服务器信息、添加服务器、删除服务器、修改服务器、获取备份任务、删除备份任务、修改备份任务和触发备份任务等.
三、数据库（sql server）
存储所有的服务器信息、数据库信息和备份任务等信息。
四、测试服务器相关信息
1.主服务器（程序部署的服务器），IP：192.168.1.101，服务器用户名：胡官进，服务器密码：@hu140817，操作系统window11，数据库实例名称：sql2008r2，数据库用户名：sa，数据库密码：hu140817；
2.待备份服务器1：IP：192.168.1.102，服务器用户名：胡官进，服务器密码：@hu140817，操作系统window server2019，数据库实例名称：sql2008r2，数据库用户名：sa，数据库密码：hu140817；
3.待备份服务器2：IP：192.168.1.103，服务器用户名：胡官进，服务器密码：@hu140817，操作系统window server2019，数据库实例名称：sql2008r2，数据库用户名：sa，数据库密码：hu140817；
……
待备份服务器n：IP：192.168.1.xxx，服务器用户名：胡官进，服务器密码：@hu140817，操作系统window server2019，数据库实例名称：sql2008r2，数据库用户名：sa，数据库密码：hu140817；

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/backup-manager.git
cd backup-manager
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
