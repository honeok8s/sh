# 自用Shell脚本备份
详细用法在shell脚本中，使用crontab定时任务

## Serverstatus探针，客户端探针存活监控
```
# KVM
curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/serverstatus_kvm.sh && chmod +x serverstatus_kvm.sh
# LXC
curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/serverstatus_lxc.sh && chmod +x serverstatus_lcx.sh
```
## NGINX日志切割 & 备份 & 删除旧日志,适用于编译安装NGINX
```
curl -sS -O https://raw.githubusercontent.com/honeok8s/shell/main/truncate_ngx_log.sh && chmod +x truncate_ngx_log.sh
```
