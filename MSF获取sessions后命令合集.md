# 核心命令 – 帮助菜单   
background – 将当前会话移动到背景变成一个session，当再次使用时再用sessions -i ID调用   
bgkill – 杀死一个背景 meterpreter 脚本   
bglist – 提供所有正在运行的后台脚本的列表   
bgrun – 作为一个后台线程运行脚本   
channel – 显示活动频道   
close – 关闭通道   
exit – 终止 meterpreter 会话   
help – 帮助菜单   
interact – 与通道进行交互   
irb – 进入 Ruby 脚本模式   
migrate – 移动到一个指定的 PID 的活动进程   
quit – 终止 meterpreter 会话   
read – 从通道读取数据   
run – 执行以后它选定的 meterpreter 脚本   
use – 加载 meterpreter 的扩展   
write – 将数据写入到一个通道   

# 文件系统命令   
cat -读取并输出到标准输出文件的内容   
cd -更改目录对受害人   
del -删除文件对受害人   
download-从受害者系统文件下载   
edit-用 vim编辑文件   
getlwd -打印本地目录   
getwd -打印工作目录   
lcd -更改本地目录   
lpwd -打印本地目录   
ls -列出在当前目录中的文件列表   
mkdir -在受害者系统上的创建目录   
pwd -输出工作目录   
rm -删除文件   
rmdir -受害者系统上删除目录   
upload-从攻击者的系统往受害者系统上传文件   

# 网络命令
portfwd -端口转发   
route -查看或修改受害者路由表   

# 系统命令
clearav -清除了受害者的计算机上的事件日志   
drop_token -被盗的令牌   
execute-执行命令   
getpid -获取当前进程 ID (PID)   
getprivs -尽可能获取尽可能多的特权   
getuid -获取作为运行服务器的用户   
kill -终止指定 PID 的进程   

ps -列出正在运行的进程   
reboot-重新启动受害人的计算机   
reg -与受害人的注册表进行交互   
rev2self -在受害者机器上调用 RevertToSelf()   

shell -在受害者计算机上打开一个shell   
shutdown-关闭了受害者的计算机   
steal_token -试图窃取指定的 (PID) 进程的令牌   
sysinfo -获取有关受害者计算机操作系统和名称等的详细信息   

# 用户界面命令
enumdesktops -列出所有可访问台式机   
getdesktop -获取当前的 meterpreter 桌面   
idletime -检查长时间以来，受害者系统空闲进程   
keyscan_dump -键盘记录软件的内容转储   
keyscan_start -启动时与如 Word 或浏览器的进程相关联的键盘记录软件   
keyscan_stop -停止键盘记录软件   
screenshot-抓去 meterpreter 桌面的屏幕截图   
set_desktop -更改 meterpreter 桌面   
uictl -启用用户界面组件的一些控件   

# 特权升级命令
getsystem -获得系统管理员权限   

# 密码转储命令
hashdump -抓去哈希密码 (SAM) 文件中的值   

# Timestomp 命令
timestomp -操作修改，访问，并创建一个文件的属性   

## 原文链接：
 https://blog.csdn.net/qq_39101049/article/details/96854716
