# 在windows下面使用tap网络

## 一、仅主机和虚拟机通信
1.安装tap网卡驱动  
2.修改网卡适配器名字为tap0  
3.打开tap0网络，设置其ip地址为192.168.0.104 (可以自由配置为本地ip)
4.在qemu中进行相关配置  
5.在程序中配置虚拟机ip地址为192.168.0.105，子网掩码为255.255.255.0，网关为192.168.0.1（主机的网关）。  
这样，虚拟机就可以和主机通信了。但是却不能和外网通信。  
注意：虚拟机的ip地址要和主机的tap网络的ip地址在同一网段。  