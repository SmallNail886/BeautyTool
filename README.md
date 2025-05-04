## 安装过程
## 需要先给termuxAPP所有文件访问权限
## termux 输入以下命令
# ⚠️不管你之前有没有执行过以下命令，现在都必须执行

## 以下是搭建指令，请逐个执行
```
(以下步骤建议打开VPN执行命令，否则无法下载XY文件)
```
```
apt upgrade
```
```
pkg install python
```
```
rm -rf $HOME/BeautyTool
```
```
git clone https://github.com/SmallNail886/BeautyTool.git
```
```
请确保出现安装成功字样(Resolving deltas : 100% , done.)才是搭建成功
```
```
(到这里请关闭VPN，否则登录不进去自己负责)
```
```
cd BeautyTool
```
```
unzip BeautyTool.zip
```
```
rm -rf BeautyTool.zip
```
```
chmod +x 权限
```
```
./权限
```
## 如果输入后报错: - CANNOT LINK EXECUTABLE '/dev/fd/3': cannot locate symbol "_ZTINSt6__ndk114basic_ofstreamIcNS_11char_traitsIcEE" referenced by "/data/data/com.termux/files/usr/tmp/...
## 那么请重新启动termux 输入指令: pkg install clang  等待执行完毕再启动XY

## Start code
```
cd BeautyTool
```
```
./权限
```
```
如果执行python脚本，出先错误问ai即可，大部分都是没有安装库
```
```
rm -rf $HOME/BeautyTool && pkg update -y && pkg upgrade -y && pkg install git -y && termux-setup-storage && git clone https://github.com/SmallNail886/BeautyTool.git && cd BeautyTool && unzip BeautyTool.zip && rm -rf BeautyTool.zip && chmod +x 指令 && ./指令 && cd && XY
```
```
