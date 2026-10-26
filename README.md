# OL启动器 Releases

此仓库只存放 OL启动器的安装包和便携版，不包含源码。

## 下载 v1.4.7

- [安装程序 OLLauncher-1.4.7-Setup.exe](https://github.com/Wuliuqi0126/ol-launcher-releases/releases/download/v1.4.7/OLLauncher-1.4.7-Setup.exe)
- [便携版 OLLauncher-1.4.7-Portable.zip](https://github.com/Wuliuqi0126/ol-launcher-releases/releases/download/v1.4.7/OLLauncher-1.4.7-Portable.zip)
- [全部版本](https://github.com/Wuliuqi0126/ol-launcher-releases/releases)

## v1.4.7 更新

- Tailscale/playit 浏览器分步引导。
- Tailscale 登录状态实时轮询，增加 `tailscale ip -4` 兜底。
- playit 运行日志解析公网隧道地址。
- 安装程序自动配置专用网络防火墙：
  - OL启动器程序放行
  - UDP 24454 发现端口
  - Java 局域网 TCP 49152–65535
  - Java TCP 25565

## SHA256

```text
A2D06D54D30BC4A89C3FE051E6F78C1A53B4766AA00F6CC19FD0EF47C95752CB  OLLauncher-1.4.7-Setup.exe
C71A05CB08A01CBB8C9EDE51A3092F2FCB371AB50D392E5E66909FADA2B6D95C  OLLauncher-1.4.7-Portable.zip
```

安装包未签名，Windows SmartScreen 可能提示，请选择“更多信息 → 仍要运行”。
