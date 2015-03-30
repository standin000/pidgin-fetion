该版本不再维护，建议使用 Openfetion 和其pidgin插件。

在跨平台即时通信软件Pidgin上实现中国移动的飞信协议。源码fork自Gradetwo的代码，现仍使用git管理，由standin000集中维护： http://github.com/standin000/fetion

目前支持飞信的聊天、发送长短信、查看用户信息等飞信基本功能。

**2010.7.31版本借鉴openfetion实现了飞信v4的登录协议，使用手机号可以正常登录啦**

如果遇到SSL失效的问题，请删除 `~/.purple/certificates/x509/tls_peers/` 下面的证书。

如果是升级，`*-SysCfg.xml`得删掉，旧的dll/so也要删掉。`*`是手机号码。

建议在此提交Bug，提交时请附带pidgin -d的输出，或附带pidgin“调试窗口”中的内容。