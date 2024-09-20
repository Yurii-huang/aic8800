# aic8800

#### 介绍
AX900双频无线USB网卡| UX9(免驱版) Linux驱动

#### 软件架构
软件架构说明
`cat /etc/os-release`（适配系统）
```
NAME="Manjaro Linux"
PRETTY_NAME="Manjaro Linux"
ID=manjaro
ID_LIKE=arch
BUILD_ID=rolling
ANSI_COLOR="32;1;24;144;200"
HOME_URL="https://manjaro.org/"
DOCUMENTATION_URL="https://wiki.manjaro.org/"
SUPPORT_URL="https://forum.manjaro.org/"
BUG_REPORT_URL="https://docs.manjaro.org/reporting-bugs/"
PRIVACY_POLICY_URL="https://manjaro.org/privacy-policy/"
LOGO=manjarolinux
```
`uname -r` （内核版本）
```bash
6.9.12-3-MANJARO
```

#### 安装使用教程

```bash
cd ./aic8000 && ./install_setup.sh
cd ./drivers/aic8000
make && make install
modprobe aic8800_fdrv
```
#### 结果贴图
![输入图片说明](https://foruda.gitee.com/images/1726843008750871894/e6b85854_4961176.png "屏幕截图")

#### 说明
源码更改来源：[https://github.com/radxa-pkg/aic8800.git](https://github.com/radxa-pkg/aic8800.git)
