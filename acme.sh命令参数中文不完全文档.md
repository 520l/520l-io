**基于acme.sh  3.0.5版本翻译命令参数中文文档（不完全版）**

#### 以下翻译基于个人目前用到的命令进行翻译，由于命令具多暂时是用到哪些常用命令就更新哪些。持续更新。

`Usage: acme.sh <command> ... [parameters ...]`		

用法：acme.sh	<命令>...[参数...]



命令：

 `-h, --help        Show this help message.`

-h, --help显示帮助信息。

 `-v, --version      Show version info.`

-v, --version显示版本信息。

 `--install        Install acme.sh to your system.`

 --install        安装acme.sh到您的系统。

 `--uninstall       Uninstall acme.sh, and uninstall the cron job.`

--uninstall       卸载acme.sh，和卸载cron任务。

 `--upgrade        Upgrade acme.sh to the latest code from https://github.com/acmesh-official/acme.sh.`

--upgrade        从[https://github.com/acmesh-official/acme.sh](https://github.com/acmesh-official/acme.sh)升级acme.sh至最新代码。

 `--issue         Issue a cert.`

 --issue         颁发证书

 `--deploy         Deploy the cert to your server.`

 --deploy         将证书部署到服务器。

 `-i, --install-cert    Install the issued cert to apache/nginx or any other server.`

 -i, --install-cert    将颁发的证书安装到apache/nginx或任何其他服务器上。

 `-r, --renew       Renew a cert.`

 -r, --renew       续订证书。

 `--renew-all       Renew all the certs.`

 --renew-all       续订所有证书。

 `--revoke         Revoke a cert.`

 --revoke         吊销证书

 `--remove         Remove the cert from list of certs known to acme.sh.`

 --remove         从 acme.sh 已知的证书列表中删除证书。

 `--list          List all the certs.`

 --list          列出所有证书。

参数：

 `-d, --domain <domain.tld>     Specifies a domain, used to issue, renew or revoke etc.`

 -d, --domain <domain.tld>     指定域，用于颁发，续订或撤销等。

 `--challenge-alias <domain.tld>  The challenge domain alias for DNS alias mode.`

​    --challenge-alias <domain.tld>  DNS 别名模式的质询域别名。

`-w, --webroot <directory>     Specifies the web root folder for web root mode.`

-w, --webroot <directory>     指定 Webroot模式的 Webroot件夹。

`--cert-file <file>        Path to copy the cert file to after issue/renew..`

--cert-file <file>       颁发/续订后将证书文件复制到的路径。

 `--key-file <file>         Path to copy the key file to after issue/renew.`

 --key-file <file>         在颁发/续订后将密钥文件复制到的路径。

 `--ca-file <file>         Path to copy the intermediate cert file to after issue/renew.`

 --ca-file <file>         在颁发/续订后将中间证书文件复制到的路径。

 `--fullchain-file <file>      Path to copy the fullchain cert file to after issue/renew.`

 --fullchain-file <file>     在颁发/续订后将完整链证书文件复制到的路径。

 `--reloadcmd <command>       Command to execute after issue/renew to reload the server.`

 --reloadcmd <command>       在颁发/续订后执行的命令以重新加载服务器。

 `--server <server_uri>       ACME Directory Resource URI. (default: https://acme.zerossl.com/v2/DV90)`

 --server <server_uri>       ACME目录资源 链接。（默认值：https://acme.zerossl.com/v2/DV90)

​         
# 原文链接：[acme.sh命令参数中文不完全文档.](https://www.yuque.com/docs/share/bcdc965d-36fa-4e00-bbad-7b9236a65501?#《acme.sh命令参数中文不完全文档》)
