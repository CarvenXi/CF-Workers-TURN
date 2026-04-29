# CF-Workers-TURN
基于 Cloudflare Workers 与 TURN 中继实现 TCP/UDP 出口代理实验，借助 TURN 协议的 TCP/UDP 中继能力突破 Workers 原生不支持 UDP 的限制，集成 VLESS over WebSocket 隧道、XUDP 多路复用及 TURN 服务扫描验证功能。
