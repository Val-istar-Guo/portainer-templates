# Portainer Templates

## 模版列表

 名称                 | 描述
 :-------------------|:---
 Nginx Proxy Manager | [Nginx Proxy Manager](https://nginxproxymanager.com/)
 shadowsocks-libev    | 仅部署`node.labels.application == shadowsocks-libev`的节点


## Labels

 名称                        | 描述
 :------------------------- | :-------
 `node.labels.application`  | 部分服务无法在任何机器上都能运行，默认识别此标签判定部署节点
