注册
登陆
创建远程仓库
通过 git clone 命令下载远程仓库到本地
git clone 会自动帮你把远程仓库下载到本地，不需要再去 git init 了
通过 clone 下来的仓库，git 有一个远程仓库地址列表，git 默认会把你 clone 的地址起一个别名：origin
然后你执行 push 的时候实际上就是将本地的版本提交到 origin 上
在本地进行操作，通过 git commit 形成历史记录
通过 git push 将本地仓库中的历史记录提交到远程仓库
本地已有仓库，需要提交到线上