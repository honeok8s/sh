# 自用Shell脚本
详细用法在shell脚本中，使用crontab定时任务

## Serverstatus探针，客户端探针存活监控
```shell
# 下载完成后自行修改Server端服务器IP地址
sed -i 's/127\.0\.0\.1/107.174.0.197/g' ./serverstatus_kvm.sh

# 适用KVM架构
curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/serverstatus_kvm.sh && chmod +x ./serverstatus_kvm.sh
# 适用LXC等小鸡架构
curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/serverstatus_lxc.sh && chmod +x ./serverstatus_lxc.sh
```
## NGINX日志管理
```shell
# 适用编译安装NGINX及基于NGINX二次开发的高性能WEB服务器日志切割备份删除
# LOG_DIR="/usr/local/nginx/logs"              日志路径可自行定义
# BAK_DIR="/usr/local/nginx/logs/backup"       日志备份路径可自行定义

curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/truncate_ngx_log.sh && chmod +x ./truncate_ngx_log.sh
```
