# MTProto Proxy IP白名单版 #

用 Python 编写的快速简便的 MTProto 代理设置。

## 启动 ##
    
1. `前往 https://github.com/comlove/MTProtoProxy_ip_white_version 下载完整代码包`
2. *选填操作* 编辑 *config.py*, 设置 **PORT**, **USERS** 和 **AD_TAG**
3. `docker-compose up -d` (或者 `python3 mtprotoproxy.py`)
4. *(（可选）获取用于共享代理的链接)* `docker-compose logs`


## 频道广告 ##

要宣传频道，请从 **@MTProxybot** 获取标签并将其放入 *config.py*.

## 性能表现 ##

代理服务器的性能应该足以轻松满足在配备 1 个 CPU 核心和 1024MB 内存的 VDS 实例上约 4000 个并发用户的需求。