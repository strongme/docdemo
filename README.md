# 演示GitTortoise使用

## 克隆服务器资源
+ 登录gitlab页面登录查找`bv/bv-doc`复制路径 （192.168.2.201进入第一个菜单）
+ 在目标目录右击选择`git clone`下一步即可

## 新建文件
+ 新建的文件或者是新加入的文件必须要操作`add`，加入到git版本控制中
+ `add`之后执行`commoit`并添加commit信息，提示这次操作进行了什么内容的更新
+ `commit`操作之后才能真正执行推送到服务器的操作`push`

## 修改文件
+ 修改文件之后只需要执行`commit`操作，无需`add`操作，因为被操作文件本身已经在`git`管理之下
+ `commit`之后执行`push`操作即可推送到服务器

## 从服务器更新别的成员提交的内容
+ 在目标目录执行`pull`操作，即可更新服务器最新内容
