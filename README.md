# 项目简介
本固件适配斐讯 N1 旁路由模式，追求轻量（请注意：不具备 PPPoE、WiFi ,IPV6相关功能）。<br>
固件包含默认皮肤、以及下列 luci-app：<br>
[luci-app-amlogic](https://github.com/ophub/luci-app-amlogic)：系统更新、文件传输、CPU 调频等<br>
[luci-app-apiyundrive-webdav](https://github.com/messense/aliyundrive-webdav)：阿里云盘webdav实现<br>
[luci-app-openclash](https://github.com/vernesong/OpenClash)<br>
[luci-app-vssr](https://github.com/xpc0938/luci-app-vssr): hello world<br>
[luci-app-passwall](https://github.com/xiaorouji/openwrt-passwall)<br>
luci-app-samba4：存储共享
luci-app-dockerman：docker 管理<br>
***
# 致谢
本项目基于 [ImmortalWrt-23.05](https://github.com/immortalwrt/immortalwrt/tree/openwrt-23.05) 源码编译，使用 flippy 的[脚本](https://github.com/unifreq/openwrt_packit)和 breakings 维护的[内核](https://github.com/breakings/OpenWrt/releases/tag/kernel_stable)打包成完整固件，感谢开发者们的无私分享。<br>
flippy 固件的更多细节参考[恩山论坛帖子](https://www.right.com.cn/forum/thread-4076037-1-1.html)。
