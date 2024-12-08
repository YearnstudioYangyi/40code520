# 40code520
加速40code访问的配置(模仿Github520)
## 一、介绍
加速40code访问，解决部分地区无法访问40code

**本项目无需安装任何程序，仅需 5 分钟。**

通过修改本地 hosts 文件，试图解决：
- 40code无法访问

让你"爱"上 40code。



*注：* 如有问题欢迎提 [issues](https://github.com/YearnstudioYangyi/40code520/issues)


## 二、使用方法

下面的地址无需访问 GitHub 即可获取到最新的 hosts 内容：

- 文件：`https://raw.hellogithub.com/hosts`
- JSON：`https://raw.hellogithub.com/hosts.json`

### 2.1 手动方式

#### 2.1.1 复制下面的内容

##### 来自[无名氏](https://www.40code.com/#page=post&id=622)
```bash
# 40code 520 Host Start
76.76.21.21 40code.com
27.124.9.52 cdn.staticfile.org
121.207.229.253 cdn.dingxiang-inc.com
222.73.168.83 static.geetest.com
125.88.253.253 lib.baomitu.com
106.127.135.218 h3v9shkh.slt.sched.tdnsv8.com
116.253.60.198 qlo33e5x.slt.sched.tdnsv8.com
# 40code 520 Host End

```


#### 2.1.2 修改 hosts 文件

hosts 文件在每个系统的位置不一，详情如下：
- Windows 系统：`C:\Windows\System32\drivers\etc\hosts`
- Linux 系统：`/etc/hosts`
- Mac（苹果电脑）系统：`/etc/hosts`
- Android（安卓）系统：`/system/etc/hosts`
- iPhone（iOS）系统：`/etc/hosts`

修改方法，把第一步的内容复制到文本末尾：

1. Windows 使用记事本。
2. Linux、Mac 使用 Root 权限：`sudo vi /etc/hosts`。
3. iPhone、iPad 须越狱、Android 必须要 root。

#### 2.1.3 激活生效
大部分情况下是直接生效，如未生效可尝试下面的办法，刷新 DNS：

1. Windows：在 CMD 窗口输入：`ipconfig /flushdns`

2. Linux 命令：`sudo nscd restart`，如报错则须安装：`sudo apt install nscd` 或 `sudo /etc/init.d/nscd restart`

3. Mac 命令：`sudo killall -HUP mDNSResponder`

**Tips：** 上述方法无效可以尝试重启机器。