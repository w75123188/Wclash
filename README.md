一、自建节点文件获取：

https://github.com/yonggekkk/Cloudflare_vless_trojan，下载_worker.js文件(注意是：现用方案是pages)具体操作步骤参照：

	https://www.youtube.com/watch?v=Kx2eUQwyWcQ

二、生成UUID，https://www.uuidgenerator.net/

	8e2ab833-7690-4085-9554-05103103cc03

三、在https://dash.cloudflare.com创建项目上传_worker.js文件

四、生成地址：

	https://pages-de9.pages.dev/8e2ab833-7690-4085-9554-05103103cc03

五、根据需要选择订阅链接：

聚合通用、Clash-meta、Sing-box订阅链接如下：

注意：以下订阅链接仅6个TLS端口节点

zhijianjiedian

聚合通用订阅链接：

	https://pages-de9.pages.dev/8e2ab833-7690-4085-9554-05103103cc03/pty	

Clash-meta订阅链接：

	https://pages-de9.pages.dev/8e2ab833-7690-4085-9554-05103103cc03/pcl	

Sing-box订阅链接：

	https://pages-de9.pages.dev/8e2ab833-7690-4085-9554-05103103cc03/psb



订阅源自定义配置文件(自定义配置文件)：

	https://raw.githubusercontent.com/liandu2024/clash/refs/heads/main/Clash-LIAN.ini
 


	https://raw.githubusercontent.com/w75123188/Wclash/refs/heads/main/Clash-LIAN.ini



openwrt主路由一键配置的方法
1分钟完美配置openClash（主路由）安格视界视频：

	https://m.youtube.com/watch?v=Hm47TyJqVdc

下载以下地址的openwt.txt文件，重命名为openwrt去掉后缀，通过ssh工具放入openwrt配置文件

	https://github.com/liandu2024/clash/blob/main/main_router/

