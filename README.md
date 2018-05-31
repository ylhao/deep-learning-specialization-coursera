# deep-learning-specialization

这个库里的内容是自己学习这门课程时完成的作业或者自己补充的一些资料、笔记等，持续更新中。

## 课程地址

[深度学习工程师微专业——吴恩达](https://mooc.study.163.com/smartSpec/detail/1001319001.htm)

## 课程相关资源

[课件、课后作业和其它资料](https://github.com/ylhao/deeplearning.ai)

## 配置环境

### 设置 pip 源

设置源主要是为了接下来提升通过 pip 安装各种包的速度。

```
// 打开相关的配置文件
vim ~/.pip/pip.conf

// 写入以下内容
 [global]
 trusted-host=mirrors.aliyun.com
 index-url=http://mirrors.aliyun.com/pypi/simple

// 保存退出
```

### 创建虚拟环境

```
sudo pip install virtualenv
virtualenv --no-site-packages --python=python3.5 venv
source venv/bin/activate
pip install numpy pandas matplotlib tensorflow=1.0.0
deactivate
```

